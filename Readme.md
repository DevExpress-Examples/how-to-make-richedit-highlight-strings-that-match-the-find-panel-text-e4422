<!-- default file list -->
*Files to look at*:

* [CustomEdit.cs](./CS/E4422/CustomRichEdit/CustomEdit.cs) (VB: [CustomEdit.vb](./VB/E4422/CustomRichEdit/CustomEdit.vb))
* [CustomEditViewInfo.cs](./CS/E4422/CustomRichEdit/CustomEditViewInfo.cs) (VB: [CustomEditViewInfo.vb](./VB/E4422/CustomRichEdit/CustomEditViewInfo.vb))
* [RepositoryItemCustomEdit.cs](./CS/E4422/CustomRichEdit/RepositoryItemCustomEdit.cs) (VB: [RepositoryItemCustomEdit.vb](./VB/E4422/CustomRichEdit/RepositoryItemCustomEdit.vb))
* [Form1.cs](./CS/E4422/Form1.cs) (VB: [Form1.vb](./VB/E4422/Form1.vb))
* [Invoice.cs](./CS/E4422/Invoice.cs) (VB: [Invoice.vb](./VB/E4422/Invoice.vb))
* [Program.cs](./CS/E4422/Program.cs) (VB: [Program.vb](./VB/E4422/Program.vb))
<!-- default file list end -->
# How to make RichEdit highlight strings that match the Find panel text


<p>Since RichEdit may contain large amounts of content, highlighting substrings may affect application performance; which is why, by default, RichEdit doesn't highlight search strings instances. In any case, Rich content includes undisplayed markup characters and the Grid includes these in the search. This example illustrates how to implement the intended functionality. It uses the Grid custom <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsGridGridView_CustomDrawCelltopic"><u>painting events</u></a> to highlight a matched string and a <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument4716"><u>custom RichEdit</u></a> to obtain the text without markup.</p>

<br/>


