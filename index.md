<html>
	<body>        		
		
 <h1>30 Random Developed Countries</h1>
		<p id="demo">Generate.</p>
    <script>
document.getElementById("demo").onclick = function() {myFunction()};
function myFunction() {
  
var words = ["Norway",
"Ireland",
"Switzerland",
"Iceland",
"Germany",
"Sweden",
"Australia",
"Netherlands",
"Denmark",
"Finland",
"Singapore",
"United Kingdom",
"Belgium",
"New Zealand",
"Canada",
"United States",
"Austria",
"Israel",
"Japan",
"Slovenia",
"Korea (Republic of)",
"Luxembourg",
"Spain",
"France",
"Czechia",
"Malta",
"Estonia",
"Italy",
"United Arab Emirates",
"Greece",
"Cyprus",
"Lithuania",
"Poland",
"Andorra",
"Latvia",
"Portugal",
"Slovakia",
"Hungary",
"Saudi Arabia",
"Bahrain",
"Chile",
"Croatia",
"Qatar",
"Argentina",
"Montenegro",
"Romania",
"Kazakhstan",
"Russian Federation",
"Belarus",
"Turkey",
"Uruguay",
"Bulgaria",
"Panama",
"Bahamas",
"Barbados",
"Oman",
"Georgia",
"Costa Rica",
"Malaysia",
"Kuwait",
"Serbia",
"Mauritius",
"Seychelles",
"Trinidad and Tobago",
"Albania",
"Cuba",
"Iran (Islamic Republic of)",
"Sri Lanka",
"Bosnia and Herzegovina",
"Grenada",
"Mexico",
"Ukraine",
"Antigua and Barbuda",
"Peru",
"Thailand",
"Armenia",
"North Macedonia",
"Colombia",
"Brazil",
"China",
"Ecuador",
"Saint Lucia",
"Azerbaijan",
"Dominican Republic",
"Moldova (Republic of)",
"Algeria",
"Lebanon",
"Fiji",
"Dominica"];

function fisherYates (arr) {
  for (var i = arr.length - 1; i >= 0; i--) {
    var j = Math.floor(Math.random() * (i + 1));
    var temp = arr[i];
    arr[i] = arr[j];
    arr[j] = temp;
  }
  return arr;
}

f=fisherYates(words);

document.getElementById("demo").innerHTML = ("<p>" + f[0] + "</p>" + "<p>" + f[1] + "</p>" + "<p>" + f[2] + "</p>" + "<p>" + f[3] + "</p>" + "<p>" + f[4] + "</p>" + "<p>" + f[5] + "</p>" + "<p>" + f[6] + "</p>" + "<p>" + f[7] + "</p>" + "<p>" + f[8] + "</p>" + "<p>" + f[9] + "</p>" + "<p>" + "<p>" + f[10] + "</p>" + "<p>"+ "<p>" + f[11] + "</p>" + "<p>"+ "<p>" + f[12] + "</p>" + "<p>"+ "<p>" + f[13] + "</p>" + "<p>"+ "<p>" + f[14] + "</p>" + "<p>"+ "<p>" + f[15] + "</p>" + "<p>"+ "<p>" + f[16] + "</p>" + "<p>"+ "<p>" + f[17] + "</p>" + "<p>"+ "<p>" + f[18] + "</p>" + "<p>"+ "<p>" + f[19] + "</p>" + "<p>"+ "<p>" + f[20] + "</p>" + "<p>"+ "<p>" + f[21] + "</p>" + "<p>"+ "<p>" + f[22] + "</p>" + "<p>"+ "<p>" + f[23] + "</p>" + "<p>"+ "<p>" + f[24] + "</p>" + "<p>"+ "<p>" + f[25] + "</p>" + "<p>"+ "<p>" + f[26] + "</p>" + "<p>"+ "<p>" + f[27] + "</p>" + "<p>"+ "<p>" + f[28] + "</p>" + "<p>"+ "<p>" + f[29] + "</p>" + "<p>");}
    </script>
    
<FORM>
<INPUT Type="button" VALUE="Reload Page" onClick="history.go(0)">
</FORM>
    <body>   

