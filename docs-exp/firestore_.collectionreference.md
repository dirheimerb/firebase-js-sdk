<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [CollectionReference](./firestore_.collectionreference.md)

## CollectionReference class

A `CollectionReference` object can be used for adding documents, getting document references, and querying for documents (using [query()](./firestore_.query.md)<!-- -->).

<b>Signature:</b>

```typescript
export declare class CollectionReference<T = DocumentData> extends Query<T> 
```
<b>Extends:</b> [Query](./firestore_.query.md)<!-- -->&lt;T&gt;

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [firestore](./firestore_.collectionreference.firestore.md) |  | [FirebaseFirestore](./firestore_.firebasefirestore.md) |  |
|  [id](./firestore_.collectionreference.id.md) |  | string | The collection's identifier. |
|  [parent](./firestore_.collectionreference.parent.md) |  | [DocumentReference](./firestore_.documentreference.md)<!-- -->&lt;[DocumentData](./firestore_.documentdata.md)<!-- -->&gt; \| null | A reference to the containing <code>DocumentReference</code> if this is a subcollection. If this isn't a subcollection, the reference is null. |
|  [path](./firestore_.collectionreference.path.md) |  | string | A string representing the path of the referenced collection (relative to the root of the database). |
|  [type](./firestore_.collectionreference.type.md) |  | (not declared) |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [withConverter(converter)](./firestore_.collectionreference.withconverter.md) |  | Applies a custom data converter to this CollectionReference, allowing you to use your own custom model objects with Firestore. When you call [addDoc()](./firestore_.adddoc.md) with the returned <code>CollectionReference</code> instance, the provided converter will convert between Firestore data and your custom type <code>U</code>. |
