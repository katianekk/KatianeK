# KatianeK
Teste Automatizado
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head profile="http://selenium-ide.openqa.org/profiles/test-case">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<link rel="selenium.base" href="http://teste-caixa:8082/" />
<title>New Test</title>
</head>
<body>
<table cellpadding="1" cellspacing="1" border="1">
<thead>
<tr><td rowspan="1" colspan="3">New Test</td></tr>
</thead><tbody>
<tr>
	<td>echo</td>
	<td>------------------------------------------------------------</td>
	<td></td>
</tr>
<tr>
	<td>echo</td>
	<td>Teste automatizado para Analista de Teste</td>
	<td></td>
</tr>
<tr>
	<td>echo</td>
	<td>------------------------------------------------------------</td>
	<td></td>
</tr>
<tr>
	<td>open</td>
	<td>https://www.google.com.br/</td>
	<td></td>
</tr>
<tr>
	<td>pause</td>
	<td>2000</td>
	<td></td>
</tr>
<tr>
	<td>type</td>
	<td>class=&quot;gLFyf gsfi&quot;</td>
	<td>Samaia</td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>id=&quot;gb&quot;</td>
	<td></td>
</tr>
<tr>
	<td>waitForElementPresent</td>
	<td>href=&quot;https://samaiait.com.br/&quot;</td>
	<td></td>
</tr>
<tr>
	<td>click</td>
	<td>href=&quot;https://samaiait.com.br/&quot;</td>
	<td></td>
</tr>
<tr>
	<td>waitForElementPresent</td>
	<td>css=a..ow-button-hover &gt; span</td>
	<td>SAIBA MAIS</td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>css=a..ow-button-hover &gt; span</td>
	<td></td>
</tr>
<tr>
	<td>click</td>
	<td>link=Contato</td>
	<td></td>
</tr>
<tr>
	<td>type</td>
	<td>id=nome</td>
	<td>Katiane Kieckhoefel</td>
</tr>
<tr>
	<td>type</td>
	<td>id=email</td>
	<td>katianekiec@gmail.com</td>
</tr>
<tr>
	<td>type</td>
	<td>id=telefone</td>
	<td>48984253734</td>
</tr>
<tr>
	<td>type</td>
	<td>id=mensagem</td>
	<td>Teste para Testes Automatizados</td>
</tr>
<tr>
	<td>clickAndWait</td>
	<td>id=enviar</td>
	<td></td>
</tr>
<tr>
	<td>verifyText</td>
	<td>css=h1</td>
	<td>Obrigado por contatar a <br />Samaia IT!</td>
</tr>
<tr>
	<td>verifyText</td>
	<td>css=p</td>
	<td>Iremos retornar o mais brevemente possível.</td>
</tr>
<tr>
	<td>verifyText</td>
	<td>//div[@id='contato_lvl01']/table/tbody/tr/td/p[2]</td>
	<td>Também é possível nos contatar através do email: contato@samaiait.com.br</td>
</tr>

</tbody></table>
</body>
</html>
