**Postion a model at any place dynamically**
position: fixed;
left: number
right: number
top: number

**=>Element: getBoundingClientRect() method**
The Element.getBoundingClientRect() method returns a DOMRect object providing information about the size of an element and its position relative to the viewport.

The returned value is a DOMRect object which is the smallest rectangle which contains the entire element, including its padding and border-width. The left, top, right, bottom, x, y, width, and height properties describe the position and size of the overall rectangle in pixels. Properties other than width and height are relative to the top-left of the viewport.
**=>position property**
difference between position relative and absolute?
CSS Position Relative vs Position Absolute
Relative - the element is positioned relative to its normal position. Absolute - the element is positioned absolutely to its first positioned parent. Fixed - the element is positioned related to the browser window.

**=>useNavigate() hoook**:
The useNavigate hook returns a function that lets you navigate programmatically

**=>lastIndexOf() method**:
Returns the last occurrence of a substring in the string.
@param searchString — The substring to search for.
@param position — The index at which to begin searching. If omitted, the search begins at the end of the string.

**=>useLocation() hook:**
this hook returns current location object used by react router. It is useful if you want to peform side effects whenever current location changes

**=>substring() method**:
Returns the substring at the specified location within a String object.
@param start — The zero-based index number indicating the beginning of the substring.
@param end
Zero-based index number indicating the end of the substring. The substring includes the characters up to, but not including, the character indicated by end. If end is omitted, the characters from start through the end of the original string are returned.

Exmample usage:
const string = "javascript inbuilt methods"
const startIndex = 0, endIndex = 11;
const result1 = string.subString(startIndex,endIndex)
result1 = "javascript"
const startIndex = 5
const result2 = string.subString(startIndex)
result2 = "cript inbuilt methods"
