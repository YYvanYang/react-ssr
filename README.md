# React SSR

### caveat
1. 客户端和服务端的渲染数据要一致。否则会有警告。

> React expects that the rendered content is identical between the server and the client. It can patch up differences in text content, but you should treat mismatches as bugs and fix them. In development mode, React warns about mismatches during hydration. There are no guarantees that attribute differences will be patched up in case of mismatches. This is important for performance reasons because in most apps, mismatches are rare, and so validating all markup would be prohibitively expensive.

#### reference

- [Server Rendering with React and React Router](https://tylermcginnis.com/react-router-server-rendering/)