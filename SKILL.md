# jsoup.jsoup Skill

Use this skill to work with Norm module `jsoup.jsoup` version 3. Use only declarations listed below.

## `jsoup.jsoup`

Source: `Connection.norm`

### `Connection`

```norm
interface Connection
```

#### `cookie`

```norm
Connection? cookie(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Connection?`

#### `cookies`

```norm
Connection? cookies(JavaMap<String, String>? arg0)
```

Parameters:

- `arg0`: `JavaMap<String, String>?`

Returns: `Connection?`

#### `followRedirects`

```norm
Connection? followRedirects(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Connection?`

#### `get`

```norm
Document? get()
```

Returns: `Document?`

#### `header`

```norm
Connection? header(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Connection?`

#### `headers`

```norm
Connection? headers(JavaMap<String, String>? arg0)
```

Parameters:

- `arg0`: `JavaMap<String, String>?`

Returns: `Connection?`

#### `ignoreContentType`

```norm
Connection? ignoreContentType(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Connection?`

#### `ignoreHttpErrors`

```norm
Connection? ignoreHttpErrors(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Connection?`

#### `maxBodySize`

```norm
Connection? maxBodySize(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Connection?`

#### `method`

```norm
Connection? method(Connection_Method? arg0)
```

Parameters:

- `arg0`: `Connection_Method?`

Returns: `Connection?`

#### `newRequest`

```norm
Connection? newRequest()
```

Returns: `Connection?`

#### `newRequest`

```norm
Connection? newRequest(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

#### `newRequest`

```norm
Connection? newRequest(URL? arg0)
```

Parameters:

- `arg0`: `URL?`

Returns: `Connection?`

#### `parser`

```norm
Connection? parser(Parser? arg0)
```

Parameters:

- `arg0`: `Parser?`

Returns: `Connection?`

#### `post`

```norm
Document? post()
```

Returns: `Document?`

#### `postDataCharset`

```norm
Connection? postDataCharset(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

#### `referrer`

```norm
Connection? referrer(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

#### `requestBody`

```norm
Connection? requestBody(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

#### `timeout`

```norm
Connection? timeout(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Connection?`

#### `url`

```norm
Connection? url(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

#### `url`

```norm
Connection? url(URL? arg0)
```

Parameters:

- `arg0`: `URL?`

Returns: `Connection?`

#### `userAgent`

```norm
Connection? userAgent(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

## `jsoup.jsoup`

Source: `Connection_Method.norm`

### `Connection_Method`

```norm
enum Connection_Method
```

#### `DELETE`

```norm
DELETE
```

#### `GET`

```norm
GET
```

#### `HEAD`

```norm
HEAD
```

#### `OPTIONS`

```norm
OPTIONS
```

#### `PATCH`

```norm
PATCH
```

#### `POST`

```norm
POST
```

#### `PUT`

```norm
PUT
```

#### `TRACE`

```norm
TRACE
```

## `jsoup.jsoup`

Source: `Document.norm`

### `Document`

```norm
class Document extends Element implements Iterable<Element>, Cloneable
```

#### `Document`

```norm
Document(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `body`

```norm
Element? body()
```

Returns: `Element?`

#### `charset`

```norm
Charset? charset()
```

Returns: `Charset?`

#### `charset`

```norm
Void charset(Charset? arg0)
```

Parameters:

- `arg0`: `Charset?`

Returns: `Void`

#### `clone`

```norm
Document? clone()
```

Returns: `Document?`

#### `createElement`

```norm
Element? createElement(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `getElementById`

```norm
Element? getElementById(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `getElementsByClass`

```norm
Elements? getElementsByClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `getElementsByTag`

```norm
Elements? getElementsByTag(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `head`

```norm
Element? head()
```

Returns: `Element?`

#### `html`

```norm
String? html()
```

Returns: `String?`

#### `html`

```norm
Element? html(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `location`

```norm
String? location()
```

Returns: `String?`

#### `outerHtml`

```norm
String? outerHtml()
```

Returns: `String?`

#### `outputSettings`

```norm
DocumentOutputSettings? outputSettings()
```

Returns: `DocumentOutputSettings?`

#### `outputSettings`

```norm
Document? outputSettings(DocumentOutputSettings? arg0)
```

Parameters:

- `arg0`: `DocumentOutputSettings?`

Returns: `Document?`

#### `select`

```norm
Elements? select(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `select`

```norm
Elements? select(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Elements?`

#### `selectFirst`

```norm
Element? selectFirst(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `selectFirst`

```norm
Element? selectFirst(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Element?`

#### `text`

```norm
String? text()
```

Returns: `String?`

#### `text`

```norm
Element? text(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `title`

```norm
String? title()
```

Returns: `String?`

#### `title`

```norm
Void title(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

## `jsoup.jsoup`

Source: `DocumentOutputSettings.norm`

### `DocumentOutputSettings`

```norm
class DocumentOutputSettings implements Cloneable
```

#### `DocumentOutputSettings`

```norm
DocumentOutputSettings(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `charset`

```norm
Charset? charset()
```

Returns: `Charset?`

#### `charset`

```norm
DocumentOutputSettings? charset(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `DocumentOutputSettings?`

#### `charset`

```norm
DocumentOutputSettings? charset(Charset? arg0)
```

Parameters:

- `arg0`: `Charset?`

Returns: `DocumentOutputSettings?`

#### `clone`

```norm
DocumentOutputSettings? clone()
```

Returns: `DocumentOutputSettings?`

#### `escapeMode`

```norm
Entities_EscapeMode? escapeMode()
```

Returns: `Entities_EscapeMode?`

#### `escapeMode`

```norm
DocumentOutputSettings? escapeMode(Entities_EscapeMode? arg0)
```

Parameters:

- `arg0`: `Entities_EscapeMode?`

Returns: `DocumentOutputSettings?`

#### `indentAmount`

```norm
Integer indentAmount()
```

Returns: `Integer`

#### `indentAmount`

```norm
DocumentOutputSettings? indentAmount(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DocumentOutputSettings?`

#### `maxPaddingWidth`

```norm
Integer maxPaddingWidth()
```

Returns: `Integer`

#### `maxPaddingWidth`

```norm
DocumentOutputSettings? maxPaddingWidth(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `DocumentOutputSettings?`

#### `outline`

```norm
Boolean outline()
```

Returns: `Boolean`

#### `outline`

```norm
DocumentOutputSettings? outline(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `DocumentOutputSettings?`

#### `prettyPrint`

```norm
Boolean prettyPrint()
```

Returns: `Boolean`

#### `prettyPrint`

```norm
DocumentOutputSettings? prettyPrint(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `DocumentOutputSettings?`

#### `syntax`

```norm
Document_OutputSettings_Syntax? syntax()
```

Returns: `Document_OutputSettings_Syntax?`

#### `syntax`

```norm
DocumentOutputSettings? syntax(Document_OutputSettings_Syntax? arg0)
```

Parameters:

- `arg0`: `Document_OutputSettings_Syntax?`

Returns: `DocumentOutputSettings?`

### `documentOutputSettingsNew`

```norm
DocumentOutputSettings documentOutputSettingsNew()
```

Returns: `DocumentOutputSettings`

## `jsoup.jsoup`

Source: `Element.norm`

### `Element`

```norm
class Element extends Node implements Iterable<Element>, Cloneable
```

#### `Element`

```norm
Element(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `addClass`

```norm
Element? addClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `appendChild`

```norm
Element? appendChild(Node? arg0)
```

Parameters:

- `arg0`: `Node?`

Returns: `Element?`

#### `appendElement`

```norm
Element? appendElement(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `appendElement`

```norm
Element? appendElement(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Element?`

#### `appendText`

```norm
Element? appendText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `attr`

```norm
String? attr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `attr`

```norm
Element? attr(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Element?`

#### `attr`

```norm
Element? attr(String? arg0, Boolean arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Boolean`

Returns: `Element?`

#### `baseUri`

```norm
String? baseUri()
```

Returns: `String?`

#### `child`

```norm
Element? child(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Element?`

#### `children`

```norm
Elements? children()
```

Returns: `Elements?`

#### `childrenSize`

```norm
Integer childrenSize()
```

Returns: `Integer`

#### `className`

```norm
String? className()
```

Returns: `String?`

#### `classNames`

```norm
JavaSet<String>? classNames()
```

Returns: `JavaSet<String>?`

#### `classNames`

```norm
Element? classNames(JavaSet<String>? arg0)
```

Parameters:

- `arg0`: `JavaSet<String>?`

Returns: `Element?`

#### `closest`

```norm
Element? closest(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `closest`

```norm
Element? closest(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Element?`

#### `data`

```norm
String? data()
```

Returns: `String?`

#### `expectFirst`

```norm
Element? expectFirst(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `getElementById`

```norm
Element? getElementById(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `getElementsByClass`

```norm
Elements? getElementsByClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `getElementsByTag`

```norm
Elements? getElementsByTag(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `hasAttr`

```norm
Boolean hasAttr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `hasClass`

```norm
Boolean hasClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `hasText`

```norm
Boolean hasText()
```

Returns: `Boolean`

#### `html`

```norm
String? html()
```

Returns: `String?`

#### `html`

```norm
Element? html(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `id`

```norm
String? id()
```

Returns: `String?`

#### `id`

```norm
Element? id(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `is`

```norm
Boolean is(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `is`

```norm
Boolean is(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Boolean`

#### `nodeName`

```norm
String? nodeName()
```

Returns: `String?`

#### `outerHtml`

```norm
String? outerHtml()
```

Returns: `String?`

#### `ownText`

```norm
String? ownText()
```

Returns: `String?`

#### `parent`

```norm
Element? parent()
```

Returns: `Element?`

#### `parents`

```norm
Elements? parents()
```

Returns: `Elements?`

#### `remove`

```norm
Void remove()
```

Returns: `Void`

#### `removeAttr`

```norm
Element? removeAttr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `removeClass`

```norm
Element? removeClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `select`

```norm
Elements? select(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `select`

```norm
Elements? select(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Elements?`

#### `selectFirst`

```norm
Element? selectFirst(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `selectFirst`

```norm
Element? selectFirst(Evaluator? arg0)
```

Parameters:

- `arg0`: `Evaluator?`

Returns: `Element?`

#### `tagName`

```norm
String? tagName()
```

Returns: `String?`

#### `tagName`

```norm
Element? tagName(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `tagName`

```norm
Element? tagName(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Element?`

#### `text`

```norm
String? text()
```

Returns: `String?`

#### `text`

```norm
Element? text(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `toggleClass`

```norm
Element? toggleClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `val`

```norm
String? val()
```

Returns: `String?`

#### `val`

```norm
Element? val(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `wholeText`

```norm
String? wholeText()
```

Returns: `String?`

#### `wrap`

```norm
Element? wrap(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

## `jsoup.jsoup`

Source: `Elements.norm`

### `Elements`

```norm
class Elements extends Nodes<Element> implements JavaList<Element>, RandomAccess, Cloneable, Serializable, Collection<Element>
```

#### `Elements`

```norm
Elements(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `addClass`

```norm
Elements? addClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `attr`

```norm
String? attr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

#### `attr`

```norm
Elements? attr(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Elements?`

#### `eachAttr`

```norm
JavaList<String>? eachAttr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaList<String>?`

#### `eachText`

```norm
JavaList<String>? eachText()
```

Returns: `JavaList<String>?`

#### `eq`

```norm
Elements? eq(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Elements?`

#### `expectFirst`

```norm
Element? expectFirst(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `first`

```norm
Element? first()
```

Returns: `Element?`

#### `hasAttr`

```norm
Boolean hasAttr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `hasClass`

```norm
Boolean hasClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `hasText`

```norm
Boolean hasText()
```

Returns: `Boolean`

#### `html`

```norm
String? html()
```

Returns: `String?`

#### `html`

```norm
Elements? html(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `is`

```norm
Boolean is(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `last`

```norm
Element? last()
```

Returns: `Element?`

#### `next`

```norm
Elements? next()
```

Returns: `Elements?`

#### `next`

```norm
Elements? next(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `not`

```norm
Elements? not(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `parents`

```norm
Elements? parents()
```

Returns: `Elements?`

#### `prev`

```norm
Elements? prev()
```

Returns: `Elements?`

#### `prev`

```norm
Elements? prev(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `remove`

```norm
Elements? remove()
```

Returns: `Elements?`

#### `remove`

```norm
Element? remove(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Element?`

#### `remove`

```norm
Boolean remove(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `removeAttr`

```norm
Elements? removeAttr(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `removeClass`

```norm
Elements? removeClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `select`

```norm
Elements? select(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `selectFirst`

```norm
Element? selectFirst(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Element?`

#### `text`

```norm
String? text()
```

Returns: `String?`

#### `toggleClass`

```norm
Elements? toggleClass(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `unwrap`

```norm
Elements? unwrap()
```

Returns: `Elements?`

#### `val`

```norm
String? val()
```

Returns: `String?`

#### `val`

```norm
Elements? val(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

#### `wrap`

```norm
Elements? wrap(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Elements?`

## `jsoup.jsoup`

Source: `JavaArrays.norm`

### `JavaStringArray`

```norm
class JavaStringArray
```

#### `JavaStringArray`

```norm
JavaStringArray(JavaStringArrayBindingToken token)
```

Parameters:

- `token`: `JavaStringArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
String? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `String?`

#### `set`

```norm
Void set(Integer index, String? value)
```

Parameters:

- `index`: `Integer`
- `value`: `String?`

Returns: `Void`

### `javaStringArrayNew`

```norm
JavaStringArray javaStringArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaStringArray`

## `jsoup.jsoup`

Source: `Jsoup.norm`

### `Jsoup`

```norm
class Jsoup
```

#### `Jsoup`

```norm
Jsoup(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `jsoupClean`

```norm
String? jsoupClean(String? arg0, String? arg1, Safelist? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Safelist?`

Returns: `String?`

### `jsoupClean`

```norm
String? jsoupClean(String? arg0, String? arg1, Safelist? arg2, DocumentOutputSettings? arg3)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Safelist?`
- `arg3`: `DocumentOutputSettings?`

Returns: `String?`

### `jsoupClean`

```norm
String? jsoupClean(String? arg0, Safelist? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Safelist?`

Returns: `String?`

### `jsoupConnect`

```norm
Connection? jsoupConnect(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Connection?`

### `jsoupIsValid`

```norm
Boolean jsoupIsValid(String? arg0, Safelist? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Safelist?`

Returns: `Boolean`

### `jsoupNewSession`

```norm
Connection? jsoupNewSession()
```

Returns: `Connection?`

### `jsoupParse`

```norm
Document? jsoupParse(File? arg0)
```

Parameters:

- `arg0`: `File?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(File? arg0, String? arg1)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(File? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(File? arg0, String? arg1, String? arg2, Parser? arg3)
```

Parameters:

- `arg0`: `File?`
- `arg1`: `String?`
- `arg2`: `String?`
- `arg3`: `Parser?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(InputStream? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `InputStream?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(InputStream? arg0, String? arg1, String? arg2, Parser? arg3)
```

Parameters:

- `arg0`: `InputStream?`
- `arg1`: `String?`
- `arg2`: `String?`
- `arg3`: `Parser?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(String? arg0, String? arg1, Parser? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Parser?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(String? arg0, Parser? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Parser?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(URL? arg0, Integer arg1)
```

Parameters:

- `arg0`: `URL?`
- `arg1`: `Integer`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(Path? arg0)
```

Parameters:

- `arg0`: `Path?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(Path? arg0, String? arg1)
```

Parameters:

- `arg0`: `Path?`
- `arg1`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(Path? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `Path?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `Document?`

### `jsoupParse`

```norm
Document? jsoupParse(Path? arg0, String? arg1, String? arg2, Parser? arg3)
```

Parameters:

- `arg0`: `Path?`
- `arg1`: `String?`
- `arg2`: `String?`
- `arg3`: `Parser?`

Returns: `Document?`

### `jsoupParseBodyFragment`

```norm
Document? jsoupParseBodyFragment(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Document?`

### `jsoupParseBodyFragment`

```norm
Document? jsoupParseBodyFragment(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Document?`

## `jsoup.jsoup`

Source: `Safelist.norm`

### `Safelist`

```norm
class Safelist
```

#### `Safelist`

```norm
Safelist(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `addAttributes`

```norm
Safelist? addAttributes(String? arg0, JavaStringArray? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `JavaStringArray?`

Returns: `Safelist?`

#### `addEnforcedAttribute`

```norm
Safelist? addEnforcedAttribute(String? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `Safelist?`

#### `addProtocols`

```norm
Safelist? addProtocols(String? arg0, String? arg1, JavaStringArray? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `JavaStringArray?`

Returns: `Safelist?`

#### `addTags`

```norm
Safelist? addTags(JavaStringArray? arg0)
```

Parameters:

- `arg0`: `JavaStringArray?`

Returns: `Safelist?`

#### `isSafeTag`

```norm
Boolean isSafeTag(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Boolean`

#### `preserveRelativeLinks`

```norm
Boolean preserveRelativeLinks()
```

Returns: `Boolean`

#### `preserveRelativeLinks`

```norm
Safelist? preserveRelativeLinks(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Safelist?`

#### `removeAttributes`

```norm
Safelist? removeAttributes(String? arg0, JavaStringArray? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `JavaStringArray?`

Returns: `Safelist?`

#### `removeEnforcedAttribute`

```norm
Safelist? removeEnforcedAttribute(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `Safelist?`

#### `removeProtocols`

```norm
Safelist? removeProtocols(String? arg0, String? arg1, JavaStringArray? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `JavaStringArray?`

Returns: `Safelist?`

#### `removeTags`

```norm
Safelist? removeTags(JavaStringArray? arg0)
```

Parameters:

- `arg0`: `JavaStringArray?`

Returns: `Safelist?`

### `safelistNew`

```norm
Safelist safelistNew()
```

Returns: `Safelist`

### `safelistNew`

```norm
Safelist safelistNew(Safelist? arg0)
```

Parameters:

- `arg0`: `Safelist?`

Returns: `Safelist`

### `safelistBasic`

```norm
Safelist? safelistBasic()
```

Returns: `Safelist?`

### `safelistBasicWithImages`

```norm
Safelist? safelistBasicWithImages()
```

Returns: `Safelist?`

### `safelistNone`

```norm
Safelist? safelistNone()
```

Returns: `Safelist?`

### `safelistRelaxed`

```norm
Safelist? safelistRelaxed()
```

Returns: `Safelist?`

### `safelistSimpleText`

```norm
Safelist? safelistSimpleText()
```

Returns: `Safelist?`

## `jsoup.jsoup.nodes`

Source: `nodes/Document_OutputSettings_Syntax.norm`

### `Document_OutputSettings_Syntax`

```norm
enum Document_OutputSettings_Syntax
```

#### `html`

```norm
html
```

#### `xml`

```norm
xml
```

## `jsoup.jsoup.nodes`

Source: `nodes/Entities_EscapeMode.norm`

### `Entities_EscapeMode`

```norm
enum Entities_EscapeMode
```

#### `base`

```norm
base
```

#### `extended`

```norm
extended
```

#### `xhtml`

```norm
xhtml
```

## `jsoup.jsoup.nodes`

Source: `nodes/Node.norm`

### `Node`

```norm
class Node implements Cloneable
```

#### `Node`

```norm
Node(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `jsoup.jsoup.parser`

Source: `parser/Parser.norm`

### `Parser`

```norm
class Parser implements Cloneable
```

#### `Parser`

```norm
Parser(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `jsoup.jsoup.select`

Source: `select/Evaluator.norm`

### `Evaluator`

```norm
class Evaluator
```

#### `Evaluator`

```norm
Evaluator(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `jsoup.jsoup.select`

Source: `select/Nodes.norm`

### `Nodes`

```norm
class Nodes<T extends Node> extends ArrayList<T> implements JavaList<T>, RandomAccess, Cloneable, Serializable, Collection<T>
```

Type parameters:

- `T` extends `Node`

#### `Nodes`

```norm
Nodes(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

