# Gemini Comparison

This document compares —

* **gemini** & **gemtext**, against
* **HTTP** & **HTML**, and also against
* **gopher** & **gophermap**

## Formatting

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">bold</th>
			<td align="center">✅</td>
			<td align="center">✗</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">italics</th>
			<td align="center">✅</td>
			<td align="center">✗</td>
			<td align="center">✗</td>
		</tr>
	</tbody>
</table>

## Identity

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">client public-key</th>
			<td align="center">✗</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">cookies</th>
			<td align="center">✅</td>
			<td align="center">✗</td>
			<td align="center">✗</td>
		</tr>
	</tbody>
</table>

## Images

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">embedded images</th>
			<td align="center">✅</td>
			<td align="center">✗</td>
			<td align="center">✗</td>
		</tr>
	</tbody>
</table>

## Links

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">inline links</th>
			<td align="center">✅</td>
			<td align="center">✗</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">line links</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✅</td>
		</tr>
		<tr>
			<th scope="row">URIs & URLs</th>
			<td  align="center">✅</td>
			<td  align="center">✅</td>
			<td  align="center">✗</td>
		</tr>
	</tbody>
</table>

## Privacy

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">encryption</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">mandatory encryption</th>
			<td align="center">✗</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">self-signed certificates</th>
			<td align="center">✗</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">self-third-party signed certificates</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
	</tbody>
</table>

## Text

<table>
	<thead>
		<tr>
			<th></th>
			<th>HTTP & HTML</th>
			<th>gemini & gemtext</th>
			<th>gopher & gophermap</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th scope="row">ASCII</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✅</td>
		</tr>
		<tr>
			<th scope="row">emoji</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
		<tr>
			<th scope="row">Unicode UTF-8</th>
			<td align="center">✅</td>
			<td align="center">✅</td>
			<td align="center">✗</td>
		</tr>
	</tbody>
</table>
