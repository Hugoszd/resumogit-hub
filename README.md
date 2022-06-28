<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Resumo GIT e GITHUB</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}


	
</style></head><body><article id="3afe4664-d0d8-4c68-8b5b-5f67cd6b614a" class="page sans"><header><h1 class="page-title">Resumo GIT e GITHUB</h1></header><div class="page-body"><p id="51537cfa-c6a7-4a48-b39a-ac3713dd463e" class=""> <strong>Resumo compilado das aulas de GIT e GITHUB da DIO e StartSe </strong></p><h1 id="0db47678-8050-44b3-98e6-ff25f35b2ec7" class="">O formato usará o resumo das aulas da StartSe, porém como a DIO abordou questões importantes de segurança, então esse conteúdo será acrescentado.

StartSe

Aula 1 Introdução </h1><ul id="c520cebf-8893-4441-ad9a-b6efe1ce6ff7" class="toggle"><li><details open=""><summary>PDF</summary><figure id="01fa4034-62e3-433b-b11b-201ced57a0ea"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1-modulo-vi-introducao-ao-git.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9e656969-d5e1-47a8-a81e-57ba2e4edf6a/1-modulo-vi-introducao-ao-git.pdf</a></div></figure></details></li></ul><ul id="4bfb8904-bcd5-4023-a6e9-e23448c10dde" class="toggle"><li><details open=""><summary>Principais controladores de versão</summary><figure id="89deb446-29ca-4a02-a2f0-3cdfd0eca5a4"><a href="https://subversion.apache.org/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Apache Subversion</div><div class="bookmark-description">&quot;Enterprise-class centralized version control for the masses&quot; Welcome to subversion.apache.org, the online home of the Apache® Subversion® software project. Subversion is an open source version control system. Founded in 2000 by CollabNet, Inc., the Subversion project and software have seen incredible success over the past decade.</div></div><div class="bookmark-href"><img src="https://subversion.apache.org/icon.png" class="icon bookmark-icon"/>https://subversion.apache.org/</div></div><img src="https://subversion.apache.org/images/svnbook-cover.jpg" class="bookmark-image"/></a></figure><figure id="e4880a4b-8526-49a2-8a01-10052ed801ce"><a href="https://www.mercurial-scm.org/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Mercurial SCM</div><div class="bookmark-description">Mercurial is a free, distributed source control management tool. It efficiently handles projects of any size and offers an easy and intuitive interface. It is fast and powerful Mercurial efficiently handles projects of any size and kind. Every clone contains the whole project history, so most actions are local, fast and convenient.</div></div><div class="bookmark-href"><img src="https://www.mercurial-scm.org/images/favicon.ico" class="icon bookmark-icon"/>https://www.mercurial-scm.org/</div></div></a></figure></details></li></ul><div id="0f653675-83a5-460a-ae98-1e6e55726a54" class="column-list"><div id="8da31671-45b1-4189-80c9-758b59b59a64" style="width:25%" class="column"><h3 id="68da3ab6-5614-44c4-ac03-fe8ee91aa541" class="">Controle de versão </h3></div><div id="39adf2b6-9e9e-4105-b8cb-bee95fc570b1" style="width:75%" class="column"><ul id="14b7aa03-c462-49d1-b5ce-9e1f068dab92" class="bulleted-list"><li style="list-style-type:disc">Nos dá uma linha do tempo do projeto (Timeline).</li></ul><ul id="3a04f596-a30d-4a26-94c5-00c3ec46a5f3" class="bulleted-list"><li style="list-style-type:disc">Trabalha com alteração de estados do arquivo.</li></ul><ul id="15508852-21e3-4842-898f-795270464f84" class="bulleted-list"><li style="list-style-type:disc">Cada estado, chamamos de snapshot.</li></ul><ul id="5e7f8c8d-dc84-45a7-b763-bbc40354109e" class="bulleted-list"><li style="list-style-type:disc">Cada mudança realizada em um arquivo aumenta a sua versão.</li></ul><ul id="98ce7764-6f18-4096-a6c7-f88f70a5075e" class="bulleted-list"><li style="list-style-type:disc">Podemos ter modificações paralelas.</li></ul><ul id="adeb5b7d-8d7e-46af-9e8c-6cfb4b41347e" class="bulleted-list"><li style="list-style-type:disc">Possibilita recuperação para qualquer estado anterior.</li></ul><ul id="178a1f8f-741b-451a-b2c5-e39a4115c944" class="bulleted-list"><li style="list-style-type:disc">Podemos comparar documentos com características diferentes.</li></ul></div></div><ul id="580c00a5-9289-406c-a66d-1721f014b354" class="toggle"><li><details open=""><summary>Exemplo de linha do tempo</summary><figure id="d8ce4837-a94e-4492-a827-5c57f5cbe37c" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/temp.jpg"><img style="width:480px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/temp.jpg"/></a></figure></details></li></ul><p id="eb1deed5-419c-4e18-ad3d-0ee08f400cd1" class="">
</p><hr id="1e5e01ad-6421-4401-a755-71e200bc35be"/><h1 id="1f2e9e33-86cd-43ae-9ac6-f0d8dc92dcc1" class="">Aula 2 Configuração do ambiente</h1><ul id="3e4a5f34-e639-473c-a91c-1f82fb1a62aa" class="toggle"><li><details open=""><summary>Instalação e documentação :</summary><figure id="a3d310f3-1e94-4c85-96b5-89bbe28c1dec"><a href="https://git-scm.com/doc" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Documentation</div><div class="bookmark-description">The entire Pro Git book written by Scott Chacon and Ben Straub is available to read online for free. Dead tree versions are available on Amazon.com.</div></div><div class="bookmark-href"><img src="https://git-scm.com/favicon.ico" class="icon bookmark-icon"/>https://git-scm.com/doc</div></div><img src="https://git-scm.com/images/video/ep3.png" class="bookmark-image"/></a></figure><figure id="22f6bd79-da99-41b3-83fb-b0cb4c84166e"><a href="https://git-scm.com/downloads" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Downloads</div><div class="bookmark-description">Git comes with built-in GUI tools ( git-gui, gitk), but there are several third-party tools for users looking for a platform-specific experience. View GUI Clients → Various Git logos in PNG (bitmap) and EPS (vector) formats are available for use in online and print projects.</div></div><div class="bookmark-href"><img src="https://git-scm.com/favicon.ico" class="icon bookmark-icon"/>https://git-scm.com/downloads</div></div><img src="https://git-scm.com/images/logo@2x.png" class="bookmark-image"/></a></figure><figure id="e53ee23b-ae93-4fed-aa42-adde996b7315"><a href="https://desktop.github.com/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">GitHub Desktop</div><div class="bookmark-description">Checkout branches with pull requests and view CI statuses See all open pull requests for your repositories and check them out as if they were a local branch, even if they&#x27;re from upstream branches or forks. See which pull requests pass commit status checks, too!</div></div><div class="bookmark-href"><img src="https://github.githubassets.com/favicon.ico" class="icon bookmark-icon"/>https://desktop.github.com/</div></div><img src="https://desktop.github.com/images/upgrade/pr-checks.png" class="bookmark-image"/></a></figure></details></li></ul><ul id="6ef05168-bc2e-401e-a4ea-8a1301634449" class="toggle"><li><details open=""><summary>PDF e material</summary><figure id="c1b0de7a-a764-48bc-b14e-4f502ba51299"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2-modulo-vi-configuracao-do-ambiente.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9eb68e89-dd8d-4ff2-9ef6-c2cb4fa9db2d/2-modulo-vi-configuracao-do-ambiente.pdf</a></div></figure><figure id="773f523b-7f19-496a-9798-9a26c9c2eff1"><a href="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f33bd948-c45b-4cba-b651-a2d0283f5785/2-tutorial-instalacao-gitbash-no-windows.docx" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title"></div></div><div class="bookmark-href">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f33bd948-c45b-4cba-b651-a2d0283f5785/2-tutorial-instalacao-gitbash-no-windows.docx</div></div></a></figure></details></li></ul><p id="951324d7-7623-4c49-a539-34bf2d955ba3" class="">
</p><h3 id="ed4ed9b2-81c2-48cc-aa65-49e81b3fed48" class="">Para ver se o git está instalado e a versão:</h3><pre id="9ae2aae1-1f9e-437d-bc15-84892e277e66" class="code"><code>git version</code></pre><h3 id="f227b81d-b8b7-4038-8db3-fd28bba62f94" class="">Vamos realizar a configuração do git bash</h3><pre id="109069b2-afb0-4488-b230-5d32d5c42073" class="code"><code>#Vamos abrir o git bash
#Para configurar o nosso nome:
git config --global user.name &quot;Hugo&quot;

#Para configurar o email:
git config --global user.email &quot;hugodiscord@outlook.com&quot;

#Por configurar a branch
git config --global init.defaultBranch main


#OBS
#-&gt;Para saber se as configurações estão setadas use:
git config --list</code></pre><h3 id="e32d355f-65af-4cbd-a080-483c65c07454" class="">Após abrir o diretório que queremos, vamos controlar a versão  com git</h3><pre id="0c62a761-18b1-4e4f-802b-43078792d82b" class="code"><code>#O comando para iniciar o git a partir do diretório é:
git init</code></pre><p id="2406b577-df78-4712-b9bd-d2e7e006f3a0" class="">
</p><hr id="ac5f1c15-dc6f-44fd-bcee-444ea2072445"/><h1 id="dfbe02fb-3e6b-4692-b9b3-62f4ecbf33f6" class="">Aula 3 Aula Ciclo de vida dos arquivos, commits e branches</h1><ul id="7855c3f3-7a26-4c4e-8887-601308adcd0e" class="toggle"><li><details open=""><summary>PDF</summary><figure id="3b391f25-5a63-4de0-9e8a-303990b2b8ab"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/3-modulo-vi-ciclo-de-vida-dos-arquivos-commits-e-branches.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/022c842f-8c95-4fd1-9002-234e16ec8f06/3-modulo-vi-ciclo-de-vida-dos-arquivos-commits-e-branches.pdf</a></div></figure></details></li></ul><div id="406ba830-9175-4f27-b6f7-d7f14199a533" class="column-list"><div id="1c3af1f3-9455-47a3-8a0d-22451055de7f" style="width:37.5%" class="column"><h3 id="9006ed4f-f9b9-495f-a562-802dcbcc3188" class=""> Git possui 4 status (ciclos) para arquivos</h3></div><div id="8ebc22b9-625f-4407-9cd1-ed50c96ad0d8" style="width:62.5%" class="column"><ol type="1" id="2146c611-12f4-4670-9c2b-139df94cbd41" class="numbered-list" start="1"><li><mark class="highlight-red">Untracked</mark> → O git não conhece a existência do arquivo em nenhuma versão (Default).</li></ol><ol type="1" id="675c1f81-e0f1-49c1-b818-f3355ee5b90b" class="numbered-list" start="2"><li><mark class="highlight-teal">Staged </mark>→ Arquivos que estão prontos para serem inseridos em um novo estado da aplicação (Novo Snapshot).</li></ol><ol type="1" id="a0bf8fe2-5456-4e63-804d-e61361a18c8e" class="numbered-list" start="3"><li><mark class="highlight-purple">Unmodified</mark> → Indica arquivo que não sofreu nenhuma modificação em relação a ultima versão.</li></ol><ol type="1" id="1c8002ff-b2a5-452f-8cd3-5fec555312eb" class="numbered-list" start="4"><li><mark class="highlight-yellow">Modified </mark>→ Indica arquivos que sofreram alteração em relação a ultima versão.</li></ol></div></div><h3 id="b625b7d6-4fdd-4265-ba29-9f2f537d4f6e" class="">Comando para ver o status dos arquivos</h3><pre id="53d0acff-1bf3-4b24-9653-d6660f487092" class="code"><code>#Num primeiro momento todos os arquivos estarão como untraked
git status</code></pre><h3 id="947c0d11-d1b8-4c6c-9730-87de1173b43e" class="">Comando para adicionar o arquivo para estado 2 Staged</h3><pre id="b95b2402-6d02-46ea-9a72-bf294c735f79" class="code"><code>#Para subir arquivo especifico:
git add nome_do_arquivo

#Caso a intenção seja adicionar todos, vamos usar o *
git add *

#OBS
#Podemos voltar o arquivo para o estado anterior com:
git reset nome_do_arquivo</code></pre><h3 id="57d7f280-2f41-4da7-928f-ca77f49368cf" class="">Comando para adicionar para o estado 3 Unmodified</h3><pre id="ec20be8d-1121-4593-bb6a-f3a378eb7c96" class="code"><code>#Vamos fazer um comentario indicando a mudança realizada com:
git commit -m &quot;comentario_entre_as_aspas&quot;</code></pre><h3 id="618646f0-6d8d-49b9-9dcf-cf9510b54c2a" class="">Para verificar os commits realizados no nosso código vamos usar:</h3><pre id="34fd1c4d-b00c-419b-b587-00fa4af9bc18" class="code"><code>#Comando para verificar quantidade de commits e as branchs utilizadas.
git log</code></pre><p id="ff291faa-4286-48db-9668-132df6b935fa" class="">
</p><div id="8c0c009c-c2fa-4180-b387-de4bc6380f38" class="column-list"><div id="c3b7f410-00ef-4487-9338-ed2aa72b40b6" style="width:18.75%" class="column"><h3 id="254f9a53-1d83-477b-89bb-f30de773230e" class="">Branch </h3></div><div id="02ea88f2-44f4-43d4-9695-47bc22f63531" style="width:81.25%" class="column"><ul id="880b21da-e474-49f0-a053-dd7941982261" class="bulleted-list"><li style="list-style-type:disc">Gera ramificações do fluxo principal de trabalho.</li></ul><ul id="f799bee9-01a5-49ab-bfd0-db46f244fefe" class="bulleted-list"><li style="list-style-type:disc">As ramificações geradas podem ser trabalhadas isoladamente.</li></ul><ul id="1c4b6902-0b30-4a1c-a3b0-7e9c8046431a" class="bulleted-list"><li style="list-style-type:disc">Após modificações faremos um merge para associar a linha do tempo principal.</li></ul><ul id="a7240edb-7d8c-46d3-8a03-a5e0febbdb90" class="toggle"><li><details open=""><summary>Exemplo</summary><figure id="a4279b2d-e7dc-413d-8793-680a1f3f994e" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1.jpg"><img style="width:936px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1.jpg"/></a></figure></details></li></ul></div></div><h3 id="077ef62f-b90a-4b1d-8928-a51e068e9528" class="">Para criar nova branch:</h3><pre id="72a32da1-e50b-4065-9b20-16865a3daf52" class="code"><code>git branch nome_da_branch</code></pre><h3 id="079f811a-f811-41d7-9035-3daee421dce7" class="">Para alterar a nossa branch de trabalho usaremos </h3><pre id="d8aa183d-0a7a-489a-99db-db53eb67f97d" class="code"><code>git checkout nome_da_branch</code></pre><p id="dbd50e6b-e62a-40af-aae9-4d4ea8097e0c" class="">Para associar o trabalho da branch que criamos a linha do tempo principal usamos:</p><pre id="4afff02d-65cd-497f-a059-73dd93323276" class="code"><code>git merge nome_da_branch</code></pre><p id="e8699e0c-bda9-47e8-906c-60cc20b98e57" class="">
</p><hr id="509bab99-08ce-4d28-9e66-1ea55e0bd927"/><h1 id="1a52c77e-804a-40ff-bad7-1bc7ba77cd20" class="">Aula 4 Branches na prática</h1><ul id="a07eeba8-99f2-4f7d-bc36-ca65b409cbe6" class="toggle"><li><details open=""><summary>PDF</summary><figure id="a5414146-5c2b-4262-a261-9c7e26b56ad9"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/4-modulo-vi-branches-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2c655c9e-613c-4283-9153-659c1ec253fb/4-modulo-vi-branches-na-pratica.pdf</a></div></figure><p id="594873ab-262f-4fc2-bd9c-6a2d97ce88da" class="">
</p></details></li></ul><div id="98b2cf7c-6529-4044-ad9f-3e24f07f852f" class="column-list"><div id="2ff6f6ab-afa9-48da-addd-45f9f2227625" style="width:25%" class="column"><h3 id="9e0a205b-89fa-4a03-83d6-10a8d3d8619b" class="">Observações:</h3></div><div id="698eb487-67bc-4b8b-a48b-271fcbf8039b" style="width:75%" class="column"><ul id="541ba00c-8ac7-4feb-ac70-aace84311386" class="bulleted-list"><li style="list-style-type:disc">Quando criamos uma branch o projeto será salvo na posição que estamos. </li></ul><ul id="686ca9cf-2c20-478b-a56c-a6a27eb8387f" class="bulleted-list"><li style="list-style-type:disc">Todas as modificações geradas numa branch são ignoradas por outras.</li></ul></div></div><h3 id="da3e6df3-080c-490d-9633-16a9382122bc" class="">Para sabermos em qual branch estamos usamos :</h3><pre id="93e959a3-f9f0-4032-9e85-55cf9cb19593" class="code"><code>#Esse comando vai mostrar a branch que estamos trabalhando.
#Também demostra todas as oturas banchs criadas no projeto.
git branch</code></pre><h3 id="f8825db2-5ba4-4991-8d0e-ced4c52e46cb" class="">Para subirmos a modificação da branch para a principal vamos usar:</h3><pre id="c04576ba-4650-431b-8137-b747e72b2827" class="code"><code>git merge Nome_da_branch

#OBS:
#Quando fazermos um merge o git gera um commit automático informando a mudança.
	#O commit será aberto no editor de texto para editarmos.

#Caso a nossa mudança impact alguma funcionalidade, o git irá nos informar.
	#Em caso de impacto, teremos a opção de escolher o que será mantido/descartado.</code></pre><h3 id="3de6b857-edd9-4bd3-9a51-972a8f66ecf0" class="">Para deletar uma branch vamos usar:</h3><pre id="0173823c-c69b-4e4b-8caa-b9432e667cb3" class="code"><code>git branch -d nome_da_branch
#OBS
#Geralmente depois de cumprida a finalidade, deletamos a branch
#Geralmente não fazemos commits da branch main diretamente.</code></pre><p id="b5bd3a00-1836-4fbd-81f9-dca0c907aec2" class="">
</p><hr id="202cf645-a669-4372-9b79-d2b852b7136c"/><h1 id="3303cfc6-d5c0-4114-a5d6-d4e5d773fe78" class="">Aula 5 Reset e diff na prática</h1><ul id="97909dca-2ded-47c9-bbbb-910cb0068fd6" class="toggle"><li><details open=""><summary>PDF</summary><figure id="a001564b-e476-44a0-a1a8-6da6e1398b26"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/5-modulo-vi-reset-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a16292ca-aa47-4d13-85aa-88cd138fc28f/5-modulo-vi-reset-na-pratica.pdf</a></div></figure></details></li></ul><div id="c607a8e1-3862-4280-a96e-0347293c4dad" class="column-list"><div id="a14a3563-631e-4c01-adcb-b61302f4435c" style="width:12.5%" class="column"><h3 id="1bba8629-a086-4082-b773-e12d4e43720b" class="">DIFF </h3></div><div id="94acb98d-09ca-4ecf-b048-16166244ddf4" style="width:87.5%" class="column"><ul id="db791264-52b0-4fd6-904f-3f840c5670ef" class="bulleted-list"><li style="list-style-type:disc">Vai mostrar a diferença entre o arquivo atual e o estado anterior.</li></ul><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="58bc0e58-9366-4be6-8723-325b7b620542"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%"><mark class="highlight-red">OBS</mark>:<p id="83594ad2-c4f1-46a8-b8b4-731a8144ad24" class="">Lembrando que o comando funciona em arquivos em staged (Quando foi feito o “git add”).</p></div></figure></div></div><h3 id="bcb5a2c1-3e67-497e-8994-94211c32ff5f" class="">Para vermos a diff entre arquivos usamos:</h3><pre id="993d50ed-cb96-47d3-ab24-dbf2d20b8d86" class="code"><code>#Nesse caso vamos ver todas as diferenças realizadas (Multiplos arquivos).
git diff

#Neste outro caso vamos ver as modificações de apenas um arquivo.
git diff nome_do_arquivo</code></pre><h3 id="72e571e8-eb9a-453e-a209-492563337525" class="">Para voltarmos ao estado anterior a modificação vamos usar:</h3><pre id="cc8d1629-5e35-464f-b079-d949f3911031" class="code"><code>#Iremos indicar o nome do arquivo para voltarmos ao ponto anterior a mudança.
git checkout nome_do_arquivo</code></pre><p id="d52ae88a-33c8-4a27-9964-28c414381a94" class="">
</p><div id="78d99d96-c031-4ad1-9366-50043f1bb59f" class="column-list"><div id="7c742285-83b5-46fb-aa56-71f347e5d3a0" style="width:18.75%" class="column"><h3 id="b4b27233-d629-4fa9-a26f-71a3b8b03b89" class="">Reset</h3></div><div id="732f1fe3-e4e3-4b06-8cbd-be6fa42f893d" style="width:81.25%" class="column"><ul id="5c4d5dd2-8de8-45b3-81a1-bc679d1a1e1d" class="bulleted-list"><li style="list-style-type:disc">Usado para voltar para o estagio anterior</li></ul><ul id="60306ac9-aec2-46c1-858d-a374ce3f365e" class="bulleted-list"><li style="list-style-type:disc">Pode ser usado de forma diferente dependendo do estado do arquivo.</li></ul></div></div><h3 id="d15a6b76-1368-4bc8-89ab-0abcfe66fb09" class="">Uso do reset na fase “staged” (Depois do “git add”)</h3><pre id="4535587c-caaf-4693-859b-43ff90425fb4" class="code"><code>#Caso tenhamos deixado passar mudança para staged vamos ter de resetar o estado
#O comando para reset para estado anterior é:
git reset nome_do_arquivogit reset nome_do_arquivo</code></pre><h3 id="81883695-ef5f-4482-989d-00f416667b26" class="">Uso do reset na fase “unmodified” (Depois do “git commit”)</h3><figure class="block-color-pink_background callout" style="white-space:pre-wrap;display:flex" id="1877d89f-f6e1-4c9e-8d5a-9912399f75f8"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%"><mark class="highlight-red">OBS</mark>: <p id="017ca6ef-d2a6-485d-84e6-97d2a53b8091" class="">1° - Termos que copiar o id do commit anterior antes de realizar o reset.</p><pre id="d073aefb-8211-4fe8-9f7d-47642d04f28f" class="code"><code>#Vamos pegar o id do commit anterior com:
git log

#Depois de aparecer todos os IDs, vamos copiar o que queremos voltar.</code></pre></div></figure><blockquote id="bf25ceaa-725c-437e-93ac-0e817b134d17" class="">Aqui vamos ter 3 formas diferentes de reset:<ul id="432330de-6b96-4b49-b996-11416285c41f" class="bulleted-list"><li style="list-style-type:disc">Reset soft (Podemos fazer commit novo)<pre id="253983a6-1fe3-4fee-9db4-ef290da0fd1a" class="code"><code>#Volta po arquivo para fase de staged
git reset --soft  nome_do_commit_anterior</code></pre></li></ul><ul id="a30d71e4-a186-46ab-b72b-6602b9210888" class="bulleted-list"><li style="list-style-type:disc">Reset mixed (Podemos fazer novo git add)<pre id="4ffa20c5-ad4e-46ec-abfd-b6756530e626" class="code"><code>#Volta o arquivo para fase de modified
git reset --mixed  nome_do_commit_anterior

#Podemos fazer a diff da modificação com o conteúdo anterior 
#Antes de fazer o &quot;git add&quot;</code></pre></li></ul><ul id="1cd779e2-668b-4ccc-8672-bf1eaf9b74eb" class="bulleted-list"><li style="list-style-type:disc">Reset hard (Desfaz tudo e volta ao estado do commit anterior)<pre id="5b987ed8-68bd-45e4-b406-ca0f48c12cf9" class="code"><code>#Vai desfazer qualquer mudança realizada desde o commit anterior.
git reset --hard  nome_do_commit_anterior</code></pre></li></ul></blockquote><p id="cb71cb19-7ce6-4977-925a-8b138e245573" class="">
</p><hr id="6d947960-5a71-4cac-8a47-8f32024152f2"/><h1 id="0c4204f0-6880-409f-a56e-837c310fb293" class="">Aula 6 GitHub, Gitlab e bitbucket</h1><ul id="dbbcd0e0-b63f-4df6-95d4-1b4ea35f3c6d" class="toggle"><li><details open=""><summary>PDF</summary><figure id="e4a1b9bb-71af-4661-af19-03a54a072ddb"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/6-modulo-vi-github-gitlab-e-bitbucket.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/27016c3d-34da-4ddd-9a77-63f167a36fa5/6-modulo-vi-github-gitlab-e-bitbucket.pdf</a></div></figure></details></li></ul><ul id="0823a025-731e-4178-8686-d188239cee81" class="toggle"><li><details open=""><summary>Páginas úteis</summary><figure id="2cbe4866-7a82-492d-b75a-0e56338210d5"><a href="https://github.com/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">GitHub: Where the world builds software</div><div class="bookmark-description">GitHub is where over 83 million developers shape the future of software, together. Contribute to the open source community, manage your Git repositories, review code like a pro, track bugs and features, power your CI/CD and DevOps workflows, and secure code before you commit it.</div></div><div class="bookmark-href"><img src="https://github.com/favicon.ico" class="icon bookmark-icon"/>https://github.com/</div></div><img src="https://github.githubassets.com/images/modules/site/social-cards/github-social.png" class="bookmark-image"/></a></figure><figure id="3addc985-d3d5-4db0-9782-98ebbad2570a"><a href="https://about.gitlab.com/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">The One DevOps Platform | GitLab</div><div class="bookmark-description">Keep everyone synchronized with powerful planning tools, regardless of your process. Whether your methodology is Waterfall or DevOps, GitLab&#x27;s simple and flexible approach to planning helps you stay organized and track progress. Now you can ensure teams are working on the right things at the right time, and maintain end-to-end visibility and traceability of issues throughout the delivery lifecycle - from idea to production.</div></div><div class="bookmark-href"><img src="https://about.gitlab.com/nuxt-images/ico/favicon.ico?cache=20220414" class="icon bookmark-icon"/>https://about.gitlab.com/</div></div><img src="https://about.gitlab.com/nuxt-images/open-graph/open-graph-gitlab.png" class="bookmark-image"/></a></figure><figure id="f5785972-37d1-4574-9d5c-450310fafbe4"><a href="https://bitbucket.org/" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Bitbucket | Git solution for teams using Jira</div><div class="bookmark-description">Bitbucket Cloud is a Git-based code and CI/CD tool optimized for teams using Jira.</div></div><div class="bookmark-href"><img src="https://wac-cdn.atlassian.com/assets/img/favicons/bitbucket/favicon-16x16.png" class="icon bookmark-icon"/>https://bitbucket.org/</div></div><img src="https://wac-cdn.atlassian.com/dam/jcr:f92b1a2a-10cd-4f82-bb2a-aa00400f4288/bitbucket-cloud-features-opengraph.png" class="bookmark-image"/></a></figure></details></li></ul><h3 id="40cf393b-0b38-48be-9bdc-5b6c2d0fe8da" class="">Podemos mandar nossas modificações locais para um repositório na nuvem</h3><figure id="01a4103d-0908-46cc-8468-c54239d6ae49" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1.jpg"><img style="width:1652px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1.jpg"/></a></figure><p id="b3d6e722-4810-4d18-bba6-3489e1bda1bd" class="">
</p><hr id="2be49a9c-c373-4892-aca4-2981bf5e45c5"/><h1 id="df496882-1ada-4e79-93a5-5ac0e6e7c1df" class=""><strong><strong>Aula 7 GitHub na Prática</strong></strong></h1><ul id="d9944d92-eefb-4967-bc36-eec3c55e1e97" class="toggle"><li><details open=""><summary>PDF</summary><figure id="dc5c68c8-9abd-4a0a-8737-cc076ea71574"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/7-modulo-vi-github-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee991d90-b747-44bb-84c3-17a6e20c8ab9/7-modulo-vi-github-na-pratica.pdf</a></div></figure></details></li></ul><h3 id="0a327af1-90d6-46d5-8b17-8f6d714453e1" class="">Aqui vamos criar um repositório no GitHub para trabalharmos com o projeto na nuvem.</h3><ul id="7a560451-dbd8-4da7-8d6b-987183ed4077" class="toggle"><li><details open=""><summary>Pegando o código do repositório da nuvem:</summary><figure id="da188f1a-0abc-4a98-9ef9-6329e34ac403" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%201.jpg"><img style="width:1919px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%201.jpg"/></a></figure></details></li></ul><ul id="7d54e114-732f-4fd7-a908-6c54a9108fb3" class="toggle"><li><details open=""><summary>Inserindo o código no repositório local</summary><figure id="fe777a24-868c-4f84-9602-499f1039e45a" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1%201.jpg"><img style="width:939px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_1%201.jpg"/></a></figure></details></li></ul><h3 id="9c600934-a96b-492e-b216-4360af5f2ffa" class="">Para conferir se inserimos corretamente o repositório</h3><pre id="74b00ad0-e920-4b33-847a-6d866d670913" class="code"><code>#Para apenas ver os repositórios remotos adicionados usamos:
git remote

#Para verificar o caminho dos repositórios adicionados vamos usar:
git remote -v</code></pre><h3 id="4fb14616-4004-4653-8c9f-af10981a758f" class="">Agora vamos enviar nossos arquivos locais para o repositório GitHub</h3><pre id="ce2aa5ee-ea1f-41f2-ab87-c42412626e01" class="code"><code>#Vamos usar o comando abaixo:
git push nome_do caminho branch_que_queremos_mandar

#No nosso caso fica:
git push origin main

#OBS
#Temos a opção de salvar o caminho automaticamente 
git push -u origin main
#Após salvar, apenas com o push já enviaremos os arquivos automáticamente.</code></pre><h3 id="4da377d1-5ffe-409d-868d-6e1e4376645a" class="">Caso a gente queira pegar os arquivos do projeto da nuvem</h3><pre id="d40ea326-c240-43dd-b536-73a2910bc69b" class="code"><code>#Lembrando que temos que pegar a URL do projeto na guia &quot;code&quot; no GitHub.
git clone url_do_projeto

#Todos os commits e branchs irão ser carregados também.</code></pre><p id="5f8136f2-c070-4a68-9e1b-069c9f3007f5" class="">
</p><hr id="0f932125-95af-4d62-b1c1-c6bfca2bcd22"/><h1 id="bb112f52-cee6-48fe-baab-9a0477685c8f" class=""><strong><strong>Aula 8 Pull e Push na Prática</strong></strong></h1><ul id="914c90fd-6d00-462e-84a1-1503c838d1aa" class="toggle"><li><details open=""><summary>PDF</summary><figure id="c60ac0e7-311a-4482-8eb4-79d226968f96"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/8-modulo-vi-pull-e-push-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/16d3a163-8a5e-42b1-8005-6dca31688b61/8-modulo-vi-pull-e-push-na-pratica.pdf</a></div></figure></details></li></ul><div id="1f8bbc90-3764-4220-9a3e-fc0f099526a0" class="column-list"><div id="c2389293-5c0c-48e9-be1d-2aaee68c864d" style="width:12.5%" class="column"><h3 id="355ffa96-5c57-453c-98c1-feb4eac9addb" class="">Git push</h3></div><div id="514cf5a5-c4a3-419b-8358-9d076ac5447e" style="width:87.5%" class="column"><ul id="6c7cb75d-444c-47ce-aa0e-d5edce97e27c" class="bulleted-list"><li style="list-style-type:disc">Usado para enviar arquivos para o repositório do projeto</li></ul></div></div><pre id="fdc8184f-5dc3-4e76-af31-3810f3e5610c" class="code"><code>#Relembrando a forma de subir os arquivos 
git push caminho_do_repositório branc_que_queremos_mandar</code></pre><p id="a95584d9-dd50-41f0-9466-4beed71d0455" class="">
</p><div id="44c5c05c-085e-47b1-8e1c-1cfc9a6785a2" class="column-list"><div id="65aacfe8-a722-4d26-b8f9-e804a2aead2b" style="width:12.5%" class="column"><h3 id="db29e259-9170-4817-ac2c-101bff9943bb" class="">Git pull</h3></div><div id="1809874a-d411-4d03-9ad9-17af5a52738c" style="width:87.5%" class="column"><ul id="f7a650f7-b9cc-46fe-b134-ea8abdfd819d" class="bulleted-list"><li style="list-style-type:disc">Usado para pegar atualizações feitas no projeto (de todas as branches)</li></ul></div></div><pre id="3e329ad7-3d82-492a-a2dc-bcda1261de30" class="code"><code>#Para pegarmos atualizações futuras feitas no código vamos usar o pull
git pull caminho_do_repositório branc_que_vamos_receber

#Vamos receber as alterações, todas as branchs e commits feitos no repositório.</code></pre><p id="b058adad-fd25-4ab7-b7b8-6678e0448b00" class="">
</p><hr id="5a3ef473-9284-4138-a0a6-e2d2e01312e1"/><h1 id="af70bb19-2a35-4f2b-a8dc-100bb2be227b" class="">Aula 9 <strong><strong>Git Merge e Rebase</strong></strong></h1><ul id="e9bee8bf-8a78-49a3-8a1c-2064ea214586" class="toggle"><li><details open=""><summary>PDF</summary><figure id="84e87a25-f94d-447b-8863-0cfc85c682af"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/9-modulo-vi-git-merge-e-rebase.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cffd540b-1402-4a6b-b6ac-4bb38c184f72/9-modulo-vi-git-merge-e-rebase.pdf</a></div></figure></details></li></ul><div id="ed7aad04-068e-4678-af77-fb083a153590" class="column-list"><div id="fa8f6536-e1a4-455a-82e9-8067f8cfc461" style="width:18.75%" class="column"><h3 id="caae99a0-3cd3-4d1f-839f-0efce41821a4" class="">Observação:</h3></div><div id="eb12ee31-577d-4b7b-b2ef-4a9da9daa944" style="width:81.25%" class="column"><p id="a24d11e1-ed29-40d2-8342-71d2cc5981d9" class="">Merge e rebase são usados para unir branches</p></div></div><div id="be4de75e-da47-459a-a835-99cc1d9addb9" class="column-list"><div id="5947950c-4d38-43be-a8f5-fda678f009ec" style="width:12.5%" class="column"><h3 id="1a697b7b-669f-48fb-a5d3-eaa30419bb31" class="">Merge</h3></div><div id="4bec42f5-466f-409d-9c2d-ed161bb87d8a" style="width:87.5%" class="column"><ul id="0a2d0422-45b0-49fe-b0d9-e020129c451c" class="bulleted-list"><li style="list-style-type:disc">Adiciona novo commit na time line principal indicando a junção das branches</li></ul><ul id="e6f686e2-63c7-4360-96b3-ea3d41e685e5" class="bulleted-list"><li style="list-style-type:disc">Gera fork do merge pra frente.</li></ul><ul id="1f55af63-b65d-416e-b1bd-28cdd9f281fd" class="toggle"><li><details open=""><summary>Visualização </summary><figure id="c8d82944-3f05-4710-9322-1ef702252f14" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%202.jpg"><img style="width:288px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%202.jpg"/></a></figure><p id="1a61b7d3-4580-4276-867f-3c8db1974f6d" class="">
</p></details></li></ul></div></div><div id="385599eb-e57a-4eaf-92db-92707071c1e9" class="column-list"><div id="64735336-ee3b-4b3a-b56e-aeabdf3250f7" style="width:12.5%" class="column"><h3 id="731ee212-385d-49e0-9fa5-7285df526c75" class="">Rebase</h3></div><div id="f8b9b671-34bd-43a0-b97d-eaecee2a221a" style="width:87.5%" class="column"><ul id="44c24cb4-3dcf-4b2f-b58d-2afa9da6e272" class="bulleted-list"><li style="list-style-type:disc">Deixa a linha do tempo linear.</li></ul><ul id="bc04f2cc-1dba-41de-b2fa-86f0efd78e40" class="bulleted-list"><li style="list-style-type:disc">Vai gerar impacto a linhas de tempo alternativas</li></ul><ul id="735dcba8-7b43-41a5-8a95-61a30e399114" class="toggle"><li><details open=""><summary>Visualização</summary><figure id="95750cb9-0511-4bed-89d2-e065f9f3e8ea" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2.jpg"><img style="width:336px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2.jpg"/></a></figure></details></li></ul></div></div><p id="947b4b00-efe6-46c5-81f0-2f50b0122253" class="">
</p><hr id="5a907821-ce3d-4d0e-b955-5b92e4075644"/><h1 id="163fc50a-5989-4085-bc89-d253b6e689d7" class="">Aula 10 <strong><strong>Merge e Rebase na Prática</strong></strong></h1><ul id="d741d00e-d0ab-4bc6-a151-3331100d6020" class="toggle"><li><details open=""><summary>PDF</summary><figure id="5a1e9588-5370-43ad-9845-2329497ee72e"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/10-modulo-vi-merge-e-rebase-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/660ae3f1-6519-4375-b2c2-3b8ad633fbc2/10-modulo-vi-merge-e-rebase-na-pratica.pdf</a></div></figure></details></li></ul><ul id="c0ddd851-e51a-46c3-969a-80e38d7a0d6f" class="toggle"><li><details open=""><summary>Extensão para ver git log no vscode</summary><figure id="cc0935bd-f580-4062-bcb3-2fd5bba69c75"><a href="https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Git History - Visual Studio Marketplace</div><div class="bookmark-description">View and search git log along with the graph and details. View a previous copy of the file. View and search the history View the history of one or all branches (git log) View the history of a file View the history of a line in a file (Git Blame).</div></div><div class="bookmark-href"><img src="https://marketplace.visualstudio.com/favicon.ico" class="icon bookmark-icon"/>https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory</div></div><img src="https://donjayamanne.gallerycdn.vsassets.io/extensions/donjayamanne/githistory/0.6.19/1635531678980/Microsoft.VisualStudio.Services.Icons.Default" class="bookmark-image"/></a></figure></details></li></ul><h3 id="c5b930af-62e1-4a0d-b4de-6289e7a0bd3b" class="">Para trabalhar com as branches</h3><pre id="98e81fa8-a56d-4e9f-94e6-f230be604beb" class="code"><code>#Para criar
git branch nome_da_branch_nova

#para trocar de branch
git checkout nome_da_branch

#Para visualizar a branch que estamos trabalhando
git branch

#Para voltar para a branch anterior 
git checkout - 

#Para criar uma branch e já mudar para ela vamos usar:
git checkout -b nome_da_branch</code></pre><h3 id="2d9f7e9a-499e-40f6-8499-8a26c1719061" class="">Para visualizarmos o fluxo dos merges e rebase vamos usar:</h3><pre id="6af0b318-efda-44fc-9004-979e1d529f84" class="code"><code>#Esse comando ira mostrar um log mais completo com linha do tempo na esquerda.
git log --graph</code></pre><p id="2cab836a-d368-4953-acac-101e68ac4c03" class="">
</p><h3 id="bfcc7d14-93a6-4a43-881f-3feb150d57ea" class=""><mark class="highlight-pink">Merge</mark> </h3><ul id="37f0071a-0c94-4344-90b2-faac1aa38e12" class="bulleted-list"><li style="list-style-type:disc">Acaba criando novo commit para nos informar que foi feito mudança e que ela foi enviada para nossa linha do tempo principal.</li></ul><pre id="878a54bc-a4c9-4ecd-9c1f-e1c6340677c9" class="code"><code>#Lembrando o comando para mergiar
git merge nome_da_outra_branch</code></pre><h3 id="9b3094c4-2da4-472c-942d-f468d2756202" class=""><mark class="highlight-purple">Rebase</mark></h3><ul id="b454b3c7-4bb0-4d0d-8ead-72ddb978d855" class="bulleted-list"><li style="list-style-type:disc">Após criar uma nova branch, fazemos um rebase com a branch “main” para atualizar a nossa time line. Vai trazer tudo na ordem cronológica.</li></ul><ul id="9f026537-e4e8-4444-b62d-36efcabfd207" class="bulleted-list"><li style="list-style-type:disc">Rebase é mais usado em branches separadas (Não usar na nossa main)</li></ul><pre id="991c0fb8-3a9b-4d69-9c2d-4176a552b5f3" class="code"><code>#Para fazer um rebase de informações para a branch que estamos vamos fazer:
git rebase nome_da_outra_branch</code></pre><p id="4cb581e4-6fad-42a4-a56d-12197cb8fba6" class="">
</p><hr id="96c2fe7f-c9ee-47b8-95fc-c5155d406f86"/><h1 id="d522fd0d-ca13-48c6-9ea3-37df4ebf7eb2" class="">Aula 11 <strong><strong>Stash na Prática</strong></strong></h1><ul id="e8486a40-a9ce-47ef-a458-b1ec0b04b427" class="toggle"><li><details open=""><summary>PDF</summary><figure id="6e168fc5-9420-4e7b-b989-93e9efb213a5"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/11-modulo-vi-stash-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7a9a369d-f46c-4c66-aa24-d6aad6da48a0/11-modulo-vi-stash-na-pratica.pdf</a></div></figure></details></li></ul><div id="f415f51c-aaee-4543-a908-cfe9b75ebf2e" class="column-list"><div id="be496eb2-5585-4dd8-8c92-fa6d074cbaca" style="width:18.75%" class="column"><p id="48988f24-bf03-4a06-83f9-709deb236d53" class="">Observações:</p></div><div id="30254ce4-5d1d-44c2-9023-9f3522f105a0" style="width:81.25%" class="column"><ul id="3068f529-4da5-474e-adb6-a25464961b5f" class="bulleted-list"><li style="list-style-type:disc">Usado para salvar o estado do nosso projeto na area temporária.</li></ul><ul id="49f65cf8-cbe2-48c3-b649-77c67e216936" class="bulleted-list"><li style="list-style-type:disc">O stash será salvo na branch que realizamos a modificação.</li></ul></div></div><h3 id="ffcabe06-4756-4f2b-9fb6-48bd59ac8509" class="">Exemplo de uso do stash</h3><pre id="b1c8e74b-8301-4adf-bee2-b122ffccb339" class="code"><code>#Salvará as alterações na area temporária.
git stash

#OBS:
#Também podemos incluir arquivos untracked no nosso stash. Ficaria:
git stash --include-untracked </code></pre><h3 id="389c3d09-37ba-4346-a0b6-18989827d259" class="">Para consultar a lista com conteúdo stash salvos usaremos:</h3><pre id="447d30df-02e6-4c8c-b1c8-cfadbf7dae70" class="code"><code>#Aqui teremos acesso a todas os &quot;stash&quot; salvos.
git stash list</code></pre><h3 id="1fe07848-23cf-43ee-a18c-85bd62b33f4b" class="">Para incorporar as alterações temporárias vamos usar:</h3><pre id="793c19fe-f4ff-4aae-9de9-fab0bb8cb2fc" class="code"><code>#Pegando as modificações da area temporaria
git stash aply</code></pre><h3 id="07e39bf6-8fa9-466f-aea7-ff1564687ce0" class="">Para limpar a lista temporária vamos usar:</h3><pre id="4fdbddba-4347-44cd-a075-75af655ccbf8" class="code"><code>#Limpando lista dos &quot;stash&#x27;s&quot;
git stash clear</code></pre><p id="f57c47d6-c481-4fcd-b15a-25066365f99d" class="">
</p><hr id="a9498ce6-94dc-4207-b8ee-c8e5da3d481f"/><h1 id="a0d3b1f9-7026-4558-b35b-e632b5d3d594" class=""><strong><strong>Aula 12 Conhecendo o .gitignore</strong></strong></h1><ul id="5e422697-a51d-4147-93c2-bb5274809b9f" class="toggle"><li><details open=""><summary>PDF</summary><figure id="dc51955a-f528-4682-8b0b-7ec54edc76b6"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/12-modulo-vi-conhecendo-o-.gitignore.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7df03942-2932-4d70-b621-d8ed62fe0502/12-modulo-vi-conhecendo-o-.gitignore.pdf</a></div></figure></details></li></ul><ul id="4420aa9f-ac73-4017-9f49-2158cf79fe39" class="toggle"><li><details open=""><summary>Paginas úteis</summary><figure id="a757fb5d-9c74-4658-b40d-128bfb509b40"><a href="https://github.com/github/gitignore" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">GitHub - github/gitignore: A collection of useful .gitignore templates</div><div class="bookmark-description">This is GitHub&#x27;s collection of file templates. We use this list to populate the .gitignore template choosers available in the GitHub.com interface when creating new repositories and files.</div></div><div class="bookmark-href"><img src="https://github.com/favicon.ico" class="icon bookmark-icon"/>https://github.com/github/gitignore</div></div><img src="https://opengraph.githubassets.com/adc8a3f6b6674fb2d829f97dda7c4e3f3757694a23ee10665d262819ff3f3522/github/gitignore" class="bookmark-image"/></a></figure><figure id="d32c2858-e685-4eeb-9fce-da284ac04a62"><a href="https://git-scm.com/docs/gitignore" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title">Git - gitignore Documentation</div><div class="bookmark-description">A gitignore file specifies intentionally untracked files that Git should ignore. Files already tracked by Git are not affected; see the NOTES below for details. Each line in a gitignore file specifies a pattern.</div></div><div class="bookmark-href"><img src="https://git-scm.com/favicon.ico" class="icon bookmark-icon"/>https://git-scm.com/docs/gitignore</div></div><img src="https://git-scm.com/images/logo@2x.png" class="bookmark-image"/></a></figure></details></li></ul><div id="d55e379b-e76a-4446-8e38-adf81b947dbb" class="column-list"><div id="94dd8fa7-78bf-4598-a714-4013f493296a" style="width:25%" class="column"><h3 id="5b72bdff-c9ab-456f-8e6a-2f84be5c61b7" class="">Observações:</h3></div><div id="255b76b5-5f5d-486c-b0e6-47c1c859704f" style="width:75%" class="column"><ul id="39b97bd5-9e04-45d7-8345-1dc63a7b3e8c" class="bulleted-list"><li style="list-style-type:disc">Delimita arquivos que não serão enviados para o repositório do nosso projeto</li></ul><ul id="4206ccaa-9d87-441c-87b5-1b98cab9cc97" class="bulleted-list"><li style="list-style-type:disc">O nome do arquivo deve ser posto dentro do documento “.gitignore” para ser ignorado.</li></ul></div></div><h3 id="34dac343-797c-4333-9517-d8e585595320" class="">Primeiro vamos ter de criar um arquivo dentro da pasta que estamos </h3><pre id="f16dd33c-7b59-4447-bbb6-334dcaccee67" class="code"><code>#O nome do arquivo vai ser &quot;.gitignore&quot; (Sem apastas)
#No terminal fica:
touch .gitignore

#Também podemos criar direto do VS code com botão direito &quot;new file&quot;.</code></pre><h3 id="66ccdd77-9920-4b14-a012-1ba662191fda" class="">Agora é só adicionar o nome do arquivo dentro do arquivo criado anteriormente.</h3><pre id="71be0a20-ec8f-4f31-a1f9-274f50190c75" class="code"><code>#Se for pelo terminal fica:
vim .gitignore

#Também podemos fazer isso de forma facilitada pelo VSCode</code></pre><p id="79f06170-3161-4e73-924b-975e4a479279" class="">
</p><hr id="d8503735-c92b-43d6-9265-4c18ab420f90"/><h1 id="d34c0158-e1bd-426c-a092-b223e7dcdc54" class=""><strong><strong>Aula 13 - Git Revert na Prática</strong></strong></h1><ul id="036c4d68-ee12-4e19-af52-768934c03ffd" class="toggle"><li><details open=""><summary>PDF</summary><figure id="70b62fd6-3c1f-4104-a91e-5799675859bd"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/13-modulo-vi-git-revert-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ba4b06ad-2563-42b2-9ab1-4abdfbb865c1/13-modulo-vi-git-revert-na-pratica.pdf</a></div></figure></details></li></ul><div id="4fc4cdf3-2a85-4413-8979-fbc58172d3b5" class="column-list"><div id="fecb35e6-1755-408b-a256-367a006df93e" style="width:25%" class="column"><h3 id="a05d1a2b-f68a-4eb8-bd59-290dd7cc0609" class="">Observações:</h3></div><div id="40d5799e-91a1-4a48-a2db-d6688eed8592" style="width:75%" class="column"><ul id="6bed0f3d-5f3b-48ed-a22d-be02faf9f2d2" class="bulleted-list"><li style="list-style-type:disc">Desfaz a alteração na time line principal.</li></ul><ul id="cb7c6a6f-6230-4432-8d0f-5108718487e2" class="bulleted-list"><li style="list-style-type:disc">Mantem a alteração na branch de origem.</li></ul><ul id="e34e139f-53f4-46bd-9b16-65b218cf10fe" class="bulleted-list"><li style="list-style-type:disc">Geralmente usamos para desfazer algo na branch main.</li></ul></div></div><h3 id="97fb2060-d365-47e7-81b0-3aadaba421e7" class="">Podemos visualizar os commits com:</h3><pre id="dfb5ab2f-a18f-4c0b-8b63-cef4886db589" class="code"><code>#Revisando
git log</code></pre><h3 id="fe798c32-dd8a-44c6-9f02-a95b0be4a1cc" class="">Para visualizar a mudança realizada em detalhes pelo commit vamos:</h3><pre id="fc25247d-8f21-48c4-ab7d-65eb0fd7db34" class="code"><code>#Depois de copiar o commit no git log, iremos usar:
git show nome_do_commit

#Será mostrada toda modificação que foi gerada.</code></pre><h3 id="1a7c3fd5-156a-4c3e-9b24-4a30339b9091" class="">Para reverter vamos fazer</h3><pre id="8d34d071-8555-4c4f-926f-16dff259fe73" class="code"><code>#Pegamos o id do commit que queremos reverter
git revert nome_do_commit_para_reverter</code></pre><p id="f72b422c-83bf-47e7-9a17-3f92cea2b717" class="">
</p><hr id="23a28680-dc3b-4b8a-87b4-10ef2bc8bf4e"/><h1 id="22b2793c-46d7-42c3-80c2-7820b8de9049" class=""><strong><strong>Aula 14 Workflows com Git</strong></strong></h1><ul id="7bb92ba8-34fb-493a-8af2-6622cb786596" class="toggle"><li><details open=""><summary>PDF</summary><figure id="887ab089-4599-4590-af59-bd8b4eccac2e"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/14-modulo-vi-workflows-com-git.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e873802-255b-4bd8-9122-cee39ed68803/14-modulo-vi-workflows-com-git.pdf</a></div></figure></details></li></ul><div id="fae7a274-dddd-4cf1-a9bd-a797cb6dac3c" class="column-list"><div id="19964a28-25f5-4d5e-bda1-bfc7be08b11e" style="width:18.75%" class="column"><p id="65b15956-d388-4e7d-bc57-30842b9bb529" class="">Observações:</p></div><div id="901e1300-41a0-4e39-be4b-28b0e50cbc9e" style="width:81.25%" class="column"><p id="3bd80d1b-51a1-48b8-a1f8-69b04cd084cc" class="">Possibilita rotina de trabalho mais consistente e produtiva.</p></div></div><h3 id="ead415a7-47de-41d0-b5f7-79f0483ab1ff" class="">Temos 3 fluxos de trabalho diferentes</h3><div id="b2a9c7a1-e4f7-4c0b-8c0e-f4e70e0d6217" class="column-list"><div id="c0af2f84-e0fb-4396-8c66-6f3609e59e9a" style="width:25%" class="column"><h3 id="9c36c604-3c50-4774-9b66-4978e03ffbc4" class=""><mark class="highlight-red">1</mark> - Centralized</h3></div><div id="87d6bc36-963f-42c5-b4f7-70930adcd6d1" style="width:75%" class="column"><ul id="bb9fd244-cfbe-4a0c-9096-ee9eb0fe2e75" class="bulleted-list"><li style="list-style-type:disc">Todos os desenvolvedores trabalham na mesma branch main.</li></ul><ul id="525d23af-25a5-41f8-93fc-909ba690743e" class="bulleted-list"><li style="list-style-type:disc">Facilita para ter organização na ordem de commits.</li></ul><ul id="ba57327d-0cd9-4589-a0c6-9f6506fd82eb" class="bulleted-list"><li style="list-style-type:disc">Geralmente usado em times muito pequenos.</li></ul><ul id="f853ae3e-0c8b-4fd9-b769-ffc99350bb42" class="toggle"><li><details open=""><summary>Modelo exemplo:</summary><figure id="248f2fc8-3c03-4ac2-8788-3255e2f23d85" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2.jpg"><img style="width:914px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2.jpg"/></a></figure></details></li></ul></div></div><div id="9406338a-3341-429d-8307-fe7d8b8636fd" class="column-list"><div id="a1e151c4-8089-4f96-9ee0-0a2394b893c2" style="width:31.25%" class="column"><h3 id="5a9c0ea3-d7dd-408b-9c09-ce93acd58bd9" class=""><mark class="highlight-yellow">2 </mark>- Feature branch</h3></div><div id="e5d89883-0fe6-4c5e-a270-7095d0ae1a25" style="width:68.75%" class="column"><ul id="c6a27bd3-66af-4806-b73f-6f90fc834081" class="bulleted-list"><li style="list-style-type:disc">Cada nova funcionalidade terá uma branch especifica.</li></ul><ul id="6dd2bf4c-c8bb-4546-a2fb-f39b19c8e5e0" class="bulleted-list"><li style="list-style-type:disc">Geralmente mais usada em times grandes.</li></ul><ul id="a379d118-2dd9-458e-b3b0-9acac5229257" class="bulleted-list"><li style="list-style-type:disc">Nesse modelo nenhum push é feito na branch main.</li></ul><ul id="8037e808-c367-43c7-a9b1-235f9f4f8db2" class="toggle"><li><details open=""><summary>Modelo exemplo:</summary><figure id="51117716-ce4f-4ef0-9be8-2ff0f2d4307e" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2%201.jpg"><img style="width:841px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_2%201.jpg"/></a></figure></details></li></ul></div></div><div id="2ce75848-508e-4df9-91d8-4a5dac166854" class="column-list"><div id="4d3d8d73-53c2-41b5-b647-0f3a2955c62c" style="width:18.75%" class="column"><h3 id="5352b9a1-8820-40ba-ba9f-d5470dd71538" class=""><mark class="highlight-orange">3</mark> - Gitflow</h3></div><div id="1e381d30-9faf-4a04-93f7-1c897c0e0376" style="width:81.25%" class="column"><ul id="1dd00e76-12c5-40df-bc7d-78acf8c99dc9" class="bulleted-list"><li style="list-style-type:disc">Cada dev vai usar um modelo estrito de branch projetada em torno do projeto.</li></ul><ul id="dddf564c-f6e8-4106-b186-fcd99ae51cc6" class="toggle"><li><details open=""><summary>Modelo</summary><figure id="8ca8a337-4524-4b3c-8d3c-51dcc4d86e1b" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_3.jpg"><img style="width:685px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Screenshot_3.jpg"/></a></figure></details></li></ul></div></div><p id="24877710-b668-497a-af4c-0799e2ca1785" class="">
</p><hr id="1a74be79-d930-4b8c-ba7c-afcbc057dc49"/><h1 id="509290a0-f883-49d4-8813-0804a2129700" class=""><strong><strong>Aula 15 - Workflow Centralizado na Prática</strong></strong></h1><ul id="affde252-264a-44a4-ab09-6a05429e5700" class="toggle"><li><details open=""><summary>PDF</summary><figure id="e3ac1af9-4957-4fd0-b33f-18229084e3bc"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/15-modulo-vi-workflow-centralizado-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c57902f5-b43b-4526-8443-be5ff60140a0/15-modulo-vi-workflow-centralizado-na-pratica.pdf</a></div></figure></details></li></ul><div id="cb6f2414-4d2a-48f7-b79f-8ff3f69542e5" class="column-list"><div id="223bedee-3871-428b-9547-46209bcec6c2" style="width:18.75%" class="column"><h3 id="43d5b2f4-0a7e-44c4-8fe4-6b8e95146451" class="">Observação: </h3></div><div id="2e1f078f-7ccb-4197-bf8a-a50992a2bfc2" style="width:81.25%" class="column"><ul id="1b2aff46-527e-41f8-ac57-cafcd74a63fc" class="bulleted-list"><li style="list-style-type:disc">Neste modelo de trabalho, precisamos sempre prezar pela organização da timeline.</li></ul><ul id="80297237-debd-4897-85f3-ac5a6c74fb86" class="bulleted-list"><li style="list-style-type:disc">Antes de fazermos push, vamos ter de fazer um pull pra organizar a cronologia do nosso trabalho (Importante !).</li></ul></div></div><h3 id="787a6dc2-4baa-41ed-b1fc-c3ab198b9638" class="">Primeiro vamos organizar a nossa timeline</h3><pre id="6cdbed24-f516-4018-b01d-9d3c0f6639b1" class="code"><code>#Nosso commit vai ficar no topo sempre.
git pull orgin main --rebase</code></pre><h3 id="8d182bf8-0b75-4a51-b3c2-1e9b86f4f324" class="">Depois de organizada, vamos fazer o push dos nossos commits</h3><pre id="11c4a4ad-8e0a-4f89-870b-dd8fec1689b3" class="code"><code>#Lembrando o comando visto anteriormente:
git push origin main</code></pre><p id="364d14fd-e096-48fa-9101-d8007a0b0626" class="">
</p><hr id="7cca4c91-405e-4ebd-8751-263b1dcb844b"/><h1 id="17d5645f-086d-4443-9073-23077b26401c" class=""><strong><strong>Aula 16 Pull Request e Feature Branch na Prática</strong></strong></h1><ul id="2f2c6fcc-8a27-4103-8a33-d0331f66a2ce" class="toggle"><li><details open=""><summary>PDF</summary><figure id="c5ef6e5e-2d43-42cc-8d90-3f745b2f0264"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/16-modulo-vi-pull-request-e-feature-branch-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1395fc6-a4fb-439c-b399-8444e39bd2f3/16-modulo-vi-pull-request-e-feature-branch-na-pratica.pdf</a></div></figure></details></li></ul><div id="1df83803-147d-496b-8681-95a732ea6838" class="column-list"><div id="4d53bde4-372c-4724-9661-9e7346c8c7e9" style="width:25%" class="column"><h3 id="cded47b5-9114-4ff5-8b79-1dc803274a0f" class="">Pull requests (PR)</h3></div><div id="5c607b01-da99-4c7a-9915-bee21c811b0d" style="width:75%" class="column"><ul id="fcf550c1-770c-4e9f-80e4-22463e6d0f2a" class="bulleted-list"><li style="list-style-type:disc">Solicitação de merge de uma branch em outra branch.</li></ul><ul id="39db31c2-9493-4b17-906a-2ebd4e2383e3" class="bulleted-list"><li style="list-style-type:disc">Geralmente usada para passar conteúdo de uma branch nossa para a main do nosso repositório remoto.</li></ul><ul id="847389ec-2020-4908-a9b1-bc7fc1952440" class="bulleted-list"><li style="list-style-type:disc">O processo de solicitação request permite que a modificação do código passe por uma avaliação antes do merge.</li></ul></div></div><h3 id="ab3ae6e3-961b-4f72-89ca-7462d2a27e49" class="">Fases até o pull request</h3><ol type="1" id="fb7073bb-98c9-48ec-a24a-c8923d2d7a7c" class="numbered-list" start="1"><li>Vamos criar uma branch da funcionalidade e fazer as mudanças.</li></ol><ol type="1" id="1a6ccb46-e49b-48f0-ab0a-cdfe3955c6b5" class="numbered-list" start="2"><li>Vamos fazer o git add e depois fazer o commit da mudança.</li></ol><ol type="1" id="bcf675be-6719-4ed9-9556-1fa1d6aceb71" class="numbered-list" start="3"><li>Vamos fazer o pull para o repositório remoto informando a branch<pre id="699a0646-71f6-488a-b94a-57acca566682" class="code"><code>git push nome_do_rep_remoto nome_da_branch_que_queremos_enviar</code></pre></li></ol><ol type="1" id="eaa13657-4888-4bb5-bdea-53d4d0965d35" class="numbered-list" start="4"><li>Agora vamos ir na página do projeto e clicar no pool request</li></ol><ol type="1" id="851a8ab8-41c4-48df-a16d-a2c8663875c8" class="numbered-list" start="5"><li>Na página de request, vamos informar pra qual branch estamos querendo mandar o conteúdo.<ul id="65824669-9a17-4764-a319-ee8996a7f187" class="bulleted-list"><li style="list-style-type:disc">Podemos fazer uma descrição do request e comentar o que foi feito</li></ul><ul id="12e4230a-09ad-4303-8015-dc72010da46d" class="bulleted-list"><li style="list-style-type:disc">Podemos marcar os revisores do código (Na opção a direita).</li></ul><ul id="2607e3f6-6e54-4e36-93bc-16fae4f88202" class="bulleted-list"><li style="list-style-type:disc">Podemos fazer sugestão para melhoria dos requests</li></ul><p id="a1ad62a6-bcab-4e5e-b0a0-591e3156f754" class="">
</p></li></ol><hr id="9d5acab4-db38-4b3c-ace8-cfe413b69b75"/><h1 id="a73628e7-2643-4126-924d-94de00f2d549" class=""><strong><strong>Aula 17 Resolvendo Conflitos na Prática</strong></strong></h1><ul id="3d0a8262-acd2-481d-a0de-65d67079dc6e" class="toggle"><li><details open=""><summary>PDF</summary><figure id="badd0d5c-24e6-4277-ac31-6a59141a0a54"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/17-modulo-vi-resolvendo-conflitos-na-pratica.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eee92eb6-81ec-47bf-9b6b-5aff74b621b2/17-modulo-vi-resolvendo-conflitos-na-pratica.pdf</a></div></figure></details></li></ul><ul id="2fe9168d-a168-4e78-bce2-69092316a92d" class="toggle"><li><details open=""><summary>Exemplo de conflito</summary><figure id="8f7ee87f-06f0-4f52-a439-e6e7d246ec94" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%203.jpg"><img style="width:928px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%203.jpg"/></a></figure><p id="e5fa57a9-f56f-4880-a69c-7b00f3b795aa" class="">
</p></details></li></ul><h3 id="a7c963ab-cafc-47ff-a0a1-c838a0c4549a" class="">No conflito temos 3 opções:</h3><div id="1a05f598-7497-4a58-9003-1b1f8d37c9fd" class="column-list"><div id="d3cf0cf1-3748-40e1-8185-2a96a0d7d7da" style="width:25%" class="column"><p id="0d8a38f9-a7e8-4f33-8a92-0cc52efdf972" class="">Accept <mark class="highlight-blue"><span style="border-bottom:0.05em solid">both</span></mark> changes</p></div><div id="f4d231e4-f09d-423e-adc2-430463f69790" style="width:75%" class="column"><ul id="61e4d0da-8645-4374-9f47-8db21e97f1b7" class="bulleted-list"><li style="list-style-type:disc">Vai incluir as 2 modificações paralelamente.</li></ul></div></div><div id="dfe0777e-67c4-43d9-9752-4274b40f2d60" class="column-list"><div id="c96e2c23-0311-49e9-9dec-51dbdcf20470" style="width:31.25%" class="column"><p id="e2f85e4d-5b8a-4957-82cc-7171000e43fe" class="">Accept <span style="border-bottom:0.05em solid"><mark class="highlight-brown">incoming</mark></span><mark class="highlight-brown"> </mark>changes</p></div><div id="283b722f-a7a8-4d6b-9da4-a63f25088c20" style="width:68.75%" class="column"><ul id="37c6a73e-c406-4913-941b-59190c70d4cb" class="bulleted-list"><li style="list-style-type:disc">Vai  aceitar a melhoria proposta pela outra branch.</li></ul></div></div><div id="d90e9613-cf41-49e7-b934-16e219f80c1a" class="column-list"><div id="0f1ec8b4-456f-4267-8d0d-53c41515a007" style="width:31.25%" class="column"><p id="28a93822-599e-4598-ab39-80e04f696e55" class="">Accept <span style="border-bottom:0.05em solid"><mark class="highlight-pink">current</mark></span><mark class="highlight-brown"> </mark>changes</p></div><div id="fd3c74e9-61ab-439b-8d54-7a1ab28536aa" style="width:68.75%" class="column"><ul id="9efa3d0a-224a-4631-8a4f-6d2f1a28e8ca" class="bulleted-list"><li style="list-style-type:disc">Vai  aceitar a melhoria proposta pela branch que estamos.</li></ul></div></div><h3 id="0ba34836-e8b6-4677-9e0e-35128a8ba9dc" class="">Após fazer a escolha da melhor opção vamos ter de fazer o git continuar</h3><figure class="block-color-red_background callout" style="white-space:pre-wrap;display:flex" id="02165261-421f-4eb9-ba8f-c87204069703"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">Lembrando que o git vai salvar o conflito e isso precisa ser enviado para a time line.<pre id="93d850ba-28dd-46da-96cf-0c2be634877c" class="code"><code>#Se for rebase vamos usar
git status</code></pre><ul id="a2c3afc3-c535-474e-960e-ff65625eb691" class="bulleted-list"><li style="list-style-type:disc">Precisamos adicionar o conflito no staged antes de prosseguir <pre id="21c3c375-08d8-43fa-b286-6dba422638d3" class="code"><code>#Adicionando arquivo 
git add nome_do_arquivo_com_conflito</code></pre></li></ul></div></figure><h3 id="bbb5f85c-cb5e-4bd8-ba78-38998fa01102" class="">Depois de adicionar, vamos ter de continuar com o rebase ou merge</h3><p id="8e5efe92-2234-4189-8972-3bdd0edffa2f" class="">Se o conflito for no rebase vamos usar:</p><pre id="a3c69333-6c40-4f41-8d82-70fa89cc5206" class="code"><code>git rebase --continue</code></pre><p id="fdf3612a-59f8-48df-9ee3-0246f610d9a0" class="">Se o conflito foi no merge vamos usar</p><pre id="54e4d9c6-5e19-403c-b23c-52f0bfbe9d9e" class="code"><code>git merge --continue</code></pre><figure class="block-color-teal_background callout" style="white-space:pre-wrap;display:flex" id="b1af636a-284a-4e0c-81ae-f06cd6cc0f34"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">O git irá criar um commit informando o conflito.<ul id="9e7d435d-5c6a-4142-8b2a-ac26009f9f0f" class="bulleted-list"><li style="list-style-type:disc">O código do conflito pode ser analisado separadamente e reincorporado caso necessário.</li></ul></div></figure><p id="40856d25-1bb4-40db-b9c6-82f72f8ed505" class="">
</p><hr id="41031ea0-9855-44ef-8d85-740fc544d2d5"/><h1 id="9ac206cc-c712-428e-90d8-4f45bd8e2411" class=""><strong><strong>Aula 18 Adicionando o site no Github Pages</strong></strong></h1><ul id="6923fdec-a4fe-48ea-9fb4-6256175d5598" class="toggle"><li><details open=""><summary>PDF</summary><figure id="9b112476-16e2-4892-812c-48c55f6fd7f5"><div class="source"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/18-modulo-vi-adicionando-o-site-no-github-pages.pdf">https://s3-us-west-2.amazonaws.com/secure.notion-static.com/848586d9-f947-4eba-8fea-d536f2379aaa/18-modulo-vi-adicionando-o-site-no-github-pages.pdf</a></div></figure></details></li></ul><div id="2539f7eb-62ab-4ba0-a480-f1960957b1db" class="column-list"><div id="e6ef8c1c-5e53-48a3-9a11-19f338bcfacf" style="width:25%" class="column"><h3 id="c5264daf-f22c-4ef9-a3d6-07b0f36db89b" class="">Observações:</h3></div><div id="ae811fa5-b8b7-4f57-b98d-d21ff6e4903b" style="width:75%" class="column"><ul id="980fffc8-27bd-4109-8dc5-a56297c3fb94" class="bulleted-list"><li style="list-style-type:disc">Podemos hospedar nosso projeto para gerar link externo.</li></ul><ul id="a03050a5-f1e9-4e66-90ad-2e6fb473eb00" class="bulleted-list"><li style="list-style-type:disc">Só consigo hospedar projetos que contem HTML, CSS e JavaScript</li></ul></div></div><h3 id="37c381ad-3cbc-4679-871d-57c4d17b6bb5" class=""><details open=""><summary>Para hospedar teremos que fazer :</summary></details></h3><div class="indented"><figure id="dbb631af-3651-4b29-be92-fc762f7eae6f" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%204.jpg"><img style="width:1870px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/1%204.jpg"/></a></figure><figure id="392faba4-8232-4cc5-8368-1f184f784e5b" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2%201.jpg"><img style="width:1840px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/2%201.jpg"/></a></figure></div><p id="f0465bdb-3db3-48a0-aab2-8298c95bfd31" class="">
</p><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="04fc7979-d3a3-439a-9677-ce8078a1192b"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">Após a hospedagem sera gerado um link que podemos compartilhar.<p id="c061558e-da72-44f7-95be-a4e614fd7ec2" class="">A base do link fica: <mark class="highlight-blue">id_do_usuário_</mark>+<mark class="highlight-yellow">.github.io</mark>+<mark class="highlight-pink">nome_do_projeto</mark></p></div></figure><p id="251977d5-6155-48c9-8166-89f21b8ca037" class="">
</p><hr id="61ef5462-fce7-41ad-bfec-da92f45e01d1"/><h1 id="2d857de0-a364-403c-b1ad-8017bd9a59cf" class="">DIO</h1><h1 id="c8012dfc-9407-4ffb-a6f6-89cf9b3086e4" class="">Tópicos fundamentais para entender o funcionamento do Git
</h1><ul id="f7903ef4-b101-4cbf-9be1-c5989b029dec" class="bulleted-list"><li style="list-style-type:disc"><strong>Entendendo como o Git funciona por baixo dos panos.</strong></li></ul><h2 id="47dc84e9-5d60-4b5d-a77a-1683da8a2e20" class="">Sha1</h2><p id="df34abff-9644-42dc-afb1-ae87325ede4c" class="">A sigla SHA significa Secure Hash Algorithm, que é um conjunto de funcões hash criptográficas projetadas pela NSA (Agência Nacional de Segurança dos EUA)

Essa encriptação gera um conjunto de caracteres identificadores com 40 dígitos.

</p><figure id="5c2b9f66-6bbd-459b-89ab-2b78a1287aac" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/echo_1.png"><img style="width:945px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/echo_1.png"/></a></figure><p id="10d5f0b9-050e-4cd7-8c52-9ddab2048d2b" class="">
</p><div id="bfe2485a-16ad-4436-a9ec-61b7ab422443" class="column-list"><div id="c9936f35-8f46-4417-9d53-aece00faa5d8" style="width:50%" class="column"><ul id="d9fb9cb3-2574-466b-bc4c-e01a2d38f5ef" class="bulleted-list"><li style="list-style-type:disc"><strong>Exemplos práticos de Sha1 </strong>

Vamos criar um bloco de notas com o nome texto.


E dentro desse desse bloco de notas, vamos escrever “Olá, meu nome é Hugo”</li></ul><p id="7df9f2ce-1c8b-487c-89fd-da5c6eb865d5" class="">
</p><p id="c1a2c4c2-c099-4684-872b-65d42c6f8b3e" class=""> </p><p id="4c177e33-a807-4a8e-9650-9d9271c91407" class="">Agora vamos gerar a chave criptográfica do bloco de notas com o comando 
“openssl sha1”
O comando será escrito da seguinte forma:</p><p id="3327ae65-3f23-4779-a9e5-b73bc1b6cfd3" class="">
</p><p id="87c78e12-3b49-4b70-b2a1-2212cebcc778" class="">Então é gerado uma chave criptografada do arquivo de texto no estado atual. </p><p id="74f12b81-dc71-4594-b4d5-a7260466d2ba" class="">
</p><p id="158d5d73-1a26-4e3c-81f6-a3779baf574e" class="">E se mudarmos o arquivo? 
Vamos adicionar uma excalamação no final, deixando “Olá, meu nome é Hugo!”</p><p id="bafdd96d-32e1-43c2-80a9-449f5ddeade9" class="">
</p><p id="9e0521a6-efae-4d00-abc5-7ac4b9712434" class="">
</p><p id="8b48f3fa-4f16-4532-96d0-8ae22923bfcc" class="">Vamos usar novamente o comando:</p><pre id="6d080e1d-adc7-4c52-b7b9-7f519f9f0b40" class="code"><code>openssl sha1 texto.txt</code></pre></div><div id="19b7368a-b8a8-4ffe-86bc-fcdd8351e50c" style="width:50%" class="column"><figure id="d37317d9-bf0f-4e39-9168-6502fdf706ec" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Texto.png"><img style="width:51px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Texto.png"/></a></figure><figure id="a3bc867c-fcdc-4019-87b4-2c9e0e6de3f2" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo1.png"><img style="width:299px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo1.png"/></a></figure><p id="2c462158-2708-4ad1-8715-01565e732830" class="">
</p><pre id="1260476e-6290-449c-8474-726e5552bb8b" class="code"><code>openssl sha1 texto.txt</code></pre><p id="3f8f078a-7761-4528-939e-6cc02f4532b2" class="">
</p><figure id="af60f9b1-537a-4111-ad93-f6169e81de2d" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_1.png"><img style="width:822px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_1.png"/></a></figure><p id="13ce780e-fcfd-4c83-8436-9c87c37a066c" class="">
</p><p id="43c37c37-ffce-40be-a664-ba3f676310fe" class="">
</p><figure id="4193eecf-ed61-48fd-94f9-1f3409638587" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo2.png"><img style="width:309px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo2.png"/></a></figure><p id="ca3b8ba9-04d6-4317-8e44-5225836cf5e8" class="">
</p><figure id="09d028f1-27de-4331-8268-33ff6210fca9" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_2.png"><img style="width:384px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_2.png"/></a></figure></div></div><div id="8f4934bc-1bc4-4539-ad5e-4b0223b59d40" class="column-list"><div id="fcc7595c-1e38-407f-8a42-ee1d24528d7f" style="width:82.75862068965522%" class="column"><p id="d69c9d43-52c6-4416-ab91-681b843948f0" class="">Com isso podemos ver que uma chave diferente foi gerada.  
devido ao ponto de exclamação no final que alterou o estado do arquivo.</p></div><div id="993c2102-1ecc-4454-b208-d5a612952618" style="width:17.241379310344833%" class="column"><p id="bc0fb181-1861-4c92-90ee-57051da53447" class="">
</p><p id="86d48334-4d64-4d1a-92e3-eb265b1c0324" class="">
</p></div></div><div id="593a7e8a-7715-431e-9daa-84fcc766eacf" class="column-list"><div id="01b987aa-25df-43e9-b33d-9c18c3897182" style="width:62.5%" class="column"><p id="0b16b195-9b5e-4b87-83e8-98aab3e865f9" class="">E se mudarmos o arquivo mais uma vez?</p></div><div id="df2febdb-7cb3-4a49-9694-f2a20e3db2c9" style="width:37.5%" class="column"><figure id="eb25588f-c35e-4ef1-95c8-0400565006c5" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo3.png"><img style="width:308px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/Hugo3.png"/></a></figure></div></div><p id="e5c14487-6c9f-4ac5-814d-44b048c073cf" class="">Novamente gera uma chave diferente.
</p><figure id="5434771e-e430-43ea-a354-8c28e97322a5" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_3.png"><img style="width:384px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/sha1_3.png"/></a></figure><p id="359dcadc-0848-4d79-9c8a-9db21cb7dc66" class="">
Então se eu mudar de volta para o estado inicial do primeiro exemplo, a chave de identificação volta ao mesmo estado também.</p><h1 id="a88a1540-b24c-4b87-b1ff-a956a8d5ceec" class="">Gerando chaves SSH e Token</h1><p id="aeacb3e0-8572-4012-b0de-6bca2a8440b4" class="">
</p><ul id="917260fd-d0fd-4051-a9a7-e9a04d9d8e97" class="bulleted-list"><li style="list-style-type:disc">Chave SSH

A chave SSH é a autenticação da sua máquina no Github, você gera uma chave SSH para declarar a sua máquina para o seu perfil no Github como máquina confiável.
Ideal para maquinas pessoais ou máquinas que somente você usa em uma empresa, pois não pede autenticações de senha durante o uso do Git e Github em conjunto.
Tornando o processo mais fácil e até mais seguro do que digitando a senha durante o uso.

Como gerar a chave?
</li></ul><pre id="604ca86e-c61a-4800-ad8f-aedcb3101c1a" class="code"><code>ssh-keygen -t ed25519 -C hugodiscord@outlook.com</code></pre><p id="2657a9d1-57ff-4854-8292-0f7c0814f8c2" class="">Observações: O ed25519 é o tipo de criptografia de segurança usada na chave, há outros tipos criptografias usados como o ed448 por exemplo, mas a mais usada, mais atual e considerada mais segura é a ed25519.
O Email é o do Github.
E o -C é usado maiúsculo mesmo.
</p><figure id="65c2af39-cd17-4f67-bcd1-d65b2870dad4" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_1.png"><img style="width:793px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_1.png"/></a></figure><p id="7d639cbd-f210-4733-bd79-03b3e3c620e0" class="">
</p><p id="e273f126-7090-42f6-b706-1a1552833c9d" class="">Essa parte será digitavel, é onde você poderá escolher o local/repositório onde a sua chave vai ficar armazenada. Caso aperte Enter sem digitar nada, ela irá para o repositório padrão conforme o ilustrado na imagem.</p><p id="2ac1fffb-fdfc-481b-866b-790cc7b2c752" class="">Se for mudar o diretório, é ideal que saiba o que está fazendo.
Por enquanto faremos o procedimento na pasta padrão mesmo.</p><p id="6ca38fca-69b4-479e-a0dd-bcd24b9b63c2" class="">O .ssh com espaço e ponto antes do nome “ssh” simboliza uma pasta oculta.
</p><figure id="bbf2dd57-8a0d-43af-bbc3-21a850517734" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_2.png"><img style="width:1601px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_2.png"/></a></figure><p id="9ed6fcaa-eb9b-4d3a-ac3b-feea854327e7" class="">
</p><p id="9f5ab554-aa00-41d0-8dcc-762c98831d56" class="">Aqui vai pedir para digitar uma senha e depois confirmar essa senha.
Observação: Essa senha é a senha de acesso do arquivo da chave e não a senha do Github.

Após as confirmações, irá para a tela da imagem logo a seguir:</p><figure id="1d45c913-be70-411c-98fc-eb263a8eb5d8" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_3.png"><img style="width:1697px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_keygen_3.png"/></a></figure><p id="f8e6f99e-23ba-429f-9283-e947fbbbbeb2" class="">
A suas chaves públicas e privadas foram geradas e salvas no diretório especificado acima. (/c/Users…. )
O SHA256 é a criptografia da sua chave SSH
E a arte aleatória criptográfica da sua chave.
</p><p id="947c46fb-370c-4cd5-895f-2d7ba512be84" class="">Então agora vamos ver a chave nos diretórios
</p><figure id="49db6a4d-5378-4098-a693-60531efa9462" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_privada_e_publica.png"><img style="width:571px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_privada_e_publica.png"/></a></figure><p id="258eea88-8140-4c22-b271-884c51de41c3" class="">
Usaremos o cd para ir no diretório da chave e o ls para vermos as chaves salvas no diretório.
Lembrando que será a chave publica que vamos expor no Github. 

Então usaremos um comando para pegarmos o código na chave pública.
</p><pre id="2798c30a-4ddd-47b8-bb28-24553aa7bf4a" class="code"><code>cat id_ed25519.pub</code></pre><figure id="597decac-71d6-47c6-8eee-9497e19947b7" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica.png"><img style="width:1846px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica.png"/></a></figure><p id="6e8574b0-7467-473e-9b1b-40f0fa0c45c8" class="">
Você receberá esse desde o ssh-ed25519, , código enorme e com o email no final, você copiará tudo, incluindo o e-mail e será usado no Github.</p><figure id="2d5187bc-4e8e-4eff-893d-7fce1678dcfb" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica_2.png"><img style="width:1515px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/chave_publica_2.png"/></a></figure><p id="6ad45b79-5677-4794-9050-7ca79a9efd2a" class="">
</p><p id="bf938b46-df7b-4ae3-a142-a9ed99cabf0e" class="">Ok, agora vamos ao Github.
E faremos o seguinte caminho:
Clique na sua foto no canto superior direto &gt; Settings &gt; e na parte esquerda selecione SSH and GPG Keys.

</p><figure id="d695efaa-6c9a-44ba-ae50-a59111e0abaa" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_chave_no_github.png"><img style="width:1507px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_chave_no_github.png"/></a></figure><p id="4140afbc-cccc-4820-9c98-cef2d04b874f" class="">
No Titile você vai dar um nome para o seu PC
E no Key você vai usar o código copiado.

</p><figure id="d9a7d880-1b88-4d3f-aeb5-a2ea7e5e5bf1" class="image"><a href="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_key_salva.png"><img style="width:1866px" src="Resumo%20GIT%20e%20GITHUB%2001fa403462e3433bb11b201ced57a0ea/ssh_key_salva.png"/></a></figure><p id="f7a2557f-6efa-46a9-bf50-0dd46a5692de" class="">E aqui você terá a confirmação da sua chave salva.

E por fim os últimos passos no Git. 
Primeiro você vai usar o comando 
</p><pre id="2c8a66b0-25c8-4563-a9cb-fd6cab5a1240" class="code"><code>eval $(ssh-agent -s)</code></pre><p id="bd86d6a1-5a21-433a-8970-c63b84d9052d" class="">Sera gerado um Agent Pid de alguns algarismos que é o começo do processo. 
E por fim o comando: </p><pre id="e4dcf197-88b5-4769-8b78-4e758998e3c8" class="code"><code>ssh-add id_ed25519</code></pre><p id="16f32ec4-f967-444b-8768-a96fa9179fad" class="">
</p><ul id="b8cb2a68-8cc8-4a17-ad3b-9d40ae469a55" class="bulleted-list"><li style="list-style-type:disc">Token 

Por fim o Token de acesso pessoal, que é a sua chave da conta por Token.

Faça o seguinte caminho:
Developer Settings &gt; Personal acess tokens &gt; Generate new token

Então na opção Note, você dará o nome da sua Token, escolherá a data de Expiração para essa Token e terá outras opções de segurança da Token. 

Por enquanto só é necessário marcar a opção repo
Você cria a chave e você receberá um código dessa chave.

<strong>Observação: </strong>O Github só te vai mostrar essa chave uma <strong>ÚNICA </strong>vez, então tenha certeza de guardar em um local bem seguro.</li></ul><p id="9d15c753-96e2-44cc-9bcf-0486bb9314c8" class="">
</p></div></article></body></html>
