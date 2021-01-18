# Day-3
__01/13/21__

## In simple terms, what is a sub-document?

Sub-documents are documents that are nested in other documents. In mongoose, they are usually schemas nested in other schemas.

## When might you use a sub-document?

Sub-documents are used when you have a list of properties with values underneath a main property. An example would be different types of moves for a game character. In each type of move, there will be multiple moves with their own values.

## How do you add to a collection of sub-documents? What about editing them?

The easiest way to add to a collection of subdocuments would be to use findOne to get the document. You would then get the array, use push to change the array, and then save it.

### Afternoon Challenge

https://github.com/JasonSpjute/planets