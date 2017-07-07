
# Socket.IO Fiddle issue-2999 report

```
$ npm install
$ npm start # run the server
$ npm run client # run the nodejs client
```

And point your browser to `https://localhost:3001`. You will need to
accept the self-sign certificate (after running generate.sh to make them) as this
is for testing purposes.

You will get the following:
```
server listening on port 3001
connect xxxxxxxxxxxxxxxxxxxx
node: ../src/util-inl.h:196: TypeName* node::Unwrap(v8::Local<v8::Object>) [with TypeName = node::TLSWrap]: Assertion `(object->InternalFieldCount()) > (0)' failed.
Aborted
```
