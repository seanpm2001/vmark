//T has-passed:no
example 9
##### src
 - foo
   - bar
	 - baz
##### xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE document SYSTEM "CommonMark.dtd">
<document xmlns="http://commonmark.org/xml/1.0">
  <list type="bullet" tight="true">
    <item>
      <paragraph>
        <text>foo</text>
      </paragraph>
      <list type="bullet" tight="true">
        <item>
          <paragraph>
            <text>bar</text>
          </paragraph>
          <list type="bullet" tight="true">
            <item>
              <paragraph>
                <text>baz</text>
              </paragraph>
            </item>
          </list>
        </item>
      </list>
    </item>
  </list>
</document>
##### html
<ul>
<li>foo
<ul>
<li>bar
<ul>
<li>baz</li>
</ul>
</li>
</ul>
</li>
</ul>
#####