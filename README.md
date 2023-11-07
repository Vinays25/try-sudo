/* with css reset */
* { box-sizing: border-box; }
table { margin: 10px; }
tr:first-child td {
	border-top-color: black;
}
tr:nth-child(3n) td {
	border-bottom-color: black;
}
td {
	border: 1px solid lightgrey;
	height: 40px;
	width: 40px;
}
td:first-child {
	border-left-color: black;
}
td:nth-child(3n) {
	border-right-color: black;
}
input {
	padding: 0;
	text-align: center;
	border: 0;
	height: 40px;
	width: 40px;
	text-align: center;
}

input:hover {
	background: #ffffff;
}
