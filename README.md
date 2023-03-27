# MWI
MWI - Matrix-Web Interface is an idea that I have to be able to update parts of
a website via [Matrix](https://matrix.org). If this goes well, this could also
be converted to other chat services with an API for bots in the future. If this
is the case, then I'll make a separate repo or website for the specification
called BWI (Bot-Web Interface).

The majority of the processing will be done on the actual website API server.
This will just convert a message from Matrix to a JSON payload like:
```JSON
{
  "type": "update.status",
  "data": "All's good"
}
```

Want to chat to me about this? I don't have a Matrix room for this yet, since I
don't think many people will be interested apart from myself. But, you can DM me
on [Matrix](https://matrix.to/#/@ludo:ludoviko.ch)
