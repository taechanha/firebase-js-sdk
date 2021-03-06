<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [onSnapshot](./firestore_.onsnapshot.md)

## onSnapshot() function

<b>Signature:</b>

```typescript
export function onSnapshot<T>(
  reference: DocumentReference<T>,
  observer: {
    next?: (snapshot: DocumentSnapshot<T>) => void;
    error?: (error: FirestoreError) => void;
    complete?: () => void;
  }
): () => void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  reference | [DocumentReference](./firestore_.documentreference.md)<!-- -->&lt;T&gt; |  |
|  observer | { next?: (snapshot: [DocumentSnapshot](./firestore_.documentsnapshot.md)<!-- -->&lt;T&gt;) =&gt; void; error?: (error: [FirestoreError](./firestore_.firestoreerror.md)<!-- -->) =&gt; void; complete?: () =&gt; void; } |  |

<b>Returns:</b>

() =&gt; void

