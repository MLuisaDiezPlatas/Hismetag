# Hismetag

<p>This repository contains  an example of output files that HisMetag tool produces.</p>
<p>There are 6 csv and two XML.</p>
<h3>1. Five of the csv</h3>
<ul>
<li><strong>All</strong> (All entities found with information)</li>
<li><strong>Org</strong>( organizations)</li>
<li><strong>Pers</strong>(persons)</li>
<li><strong>Places</strong></li>
<li><strong>Roles</strong></li></ul>

<p>This csv contain this information:
<ul> <li>For all entities :<br/>
TERM<br/> POSITION(character)<br/> WORD(number of word)<br/> TYPE (type of entity)<br/> MODE(found or proposed)<br/>AMBIGUOUS (yes or not)<br/>ANOTHER_MEANING(type of entity that produces the ambiguity)<br/>VERIFICATION(if it needs verification by expert)<br/></li>

<li>In adition, for places:<br/> URI( if it found in a gazetteer)<br/> CURRENT_TERM(current term, if the current Spanish term has been identified)<br/> DESCRIPTION (description of the place if the gazeteer in which it has been found provides it) <br/>GAZETTEER(gazetteer where found)<br/> GEO(latitude and longitude if available)<br/>
</ul>

<h3>2.The other csv(without prefixes in the name) is used to generate the dependencies and extract the attributes)</h3>


<h3>3. On the other hand it produces an XML file, prepared for visualization as HTML, and an XML-TEI file with the labeled text.</h3>

