# test_readme_quirks
<style>
.tooltip {
  display: inline;
  position: relative;
}
.tooltip:hover:after{
  display: -webkit-flex;
  display: flex;
  -webkit-justify-content: center;
  justify-content: center;
  background: #444;
  border-radius: 8px;
  color: #fff;
  content: attr(title);
  margin: -82px auto 0;
  font-size: 16px;
  padding: 13px;
  width: 220px;
}
.tooltip:hover:before{
  border: solid;
  border-color: #444 transparent;
  border-width: 12px 6px 0 6px;
  content: "";
  left: 45%;
  bottom: 30px;
  position: absolute;
}
</style>

[id1]: ## "Data is commonly used as another word for information. Oftentimes data is gathered in a specific format suitable for use on a computer (e.g., a spreadsheet). Data is a crucial ingredient in many artificial intelligence systems."

Here we define the word [data][id1] example. and allow people to quickly check the definition.
