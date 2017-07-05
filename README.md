## Installation

Copy the generated snippets folder to a new folder under your .vscode/extensions folder and restart VS Code.

## Snippets

*	``for`` - foreach ``#foreach( $var in $!{colection} ) ... #end``
*	``param`` - get url param ``$!{request.getParameter( 'someparameter' )}``
*	``host`` - get host name ``$!{link.getHost()}``
*	``if`` - if structure, without else ``#if(condition) ... #end``
*	``ifel`` - if else structure ``#if(condition) ... #else ... #end``
*	``ifparam`` - if some url param ``#if($!{request.getParameter( 'someparameter' )}) ... #end``
*	``el`` - only an else ``#else``
*	``set`` - set ``#set( $var = _value_ )``
*	``read`` - gets the content of file ``$_reader.read("path/to/file.ext")``
*	``$`` - use variable ``$!{var}``
*	``!`` - html comment ``<!-- ... -->``
*	``vm`` - velocity head ``#!vm;utf-8``
*	``+`` - addition ``$math.add($number, $number)``
*	``-`` - subtraction ``$math.sub($number, $number)``
*	``*`` - multiplication ``$math.mul($number, $number)``
*	``/`` - division ``$math.div($number, $number)``
*	``debug`` - html output debug with parameter
*	``par`` - parse ``#parse("url")``
*	``exist`` - return a boolean if file exists ``$include.exists("filepath")``
*	``isweb`` - return a boolean if plataform is web ``$_userAgent.isWeb()``
*	``issmart`` - return a boolean if plataform is smart ``$_userAgent.isSmart()``
*	``isfeature`` - return a boolean if plataform is feature ``$_userAgent.isFeature()``
*	``jsontos`` - velocity object to string ``$_json.toString(obj)``
*	``request`` - return of the url requested ``$_json.request(url)``
*	``ept`` - is empty? ``.isEmpty()``
*	``dateFormat`` - date format ``$date.format("pattern", $date.getSystemTime())``
*	``sysdate`` - system date ``$date.getSystemTime()``
*	``count`` - Velocity counter, foreach index ``$velocityCount``
*	``.up`` - Velocity toUpperCase ``.toUpperCase()``
*	``.str`` - converts to string ``.toString()``
*	``.ks`` - Object keys to Array ``.keySet()``
*	``st`` - STOP!!! Hammer time! ``#stop``
*	``ctype`` - set the content type of header's request ``$response.setContentType("type")``
*	``map`` - ``\r\n#set (\\$${1:mapName}= {})\r\n\t$!${1:mapName}.put('${2}','${0}') ##``
*	``mapPut`` - ``$!${1:mapName}.put('${2}','${0}') ##``
*	``indexOf`` - ``.indexOf(\\$${1:string})``
*	``substring`` - ``.substring(0)``
*	``size`` - ``.size()``
*	``formatCurrency`` - ``$!number.format('#,##0.00', \\$${1:number}))``
*	``formatBankAcct`` - ``$!number.formatAccountNumber(\\$${1:number})``