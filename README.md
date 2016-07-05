# formatXML
formatXML.js is a simple javascript snippet which formats &amp; indents XML for you.

Initially published at https://gist.github.com/sente/1083506

    formatXML('<foo><bar><baz>blahblah</baz><baz>tralala</baz></bar></foo>');

returns

    "<foo>
      <bar>
        <baz>blahblah</baz>
        <baz>tralala</baz>
      </bar>
    </foo>
    "
