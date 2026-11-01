<a href="https://github.com/hlang-tech/hlang"><img src="https://raw.githubusercontent.com/hlang-tech/hlang/main/media/brand/readme-banner.svg" alt="hlang — A FBP-Inspired language for building universal applications." width="100%"></a>

<p align="center">
  <b>A FBP-Inspired language for building universal applications.</b>
  <br />
  <em>Hlang aims to make programming easier, faster and more comfortable. It avoids coding, repetition and frustration.</em>
</p>

[Source](https://github.com/hlang-tech/hlang) · [npm](https://www.npmjs.com/org/hlang-org) · [Website](https://hlang.tech) · [Documentation](https://hlang.tech/docs) · [简体中文](https://github.com/hlang-tech/hlang/blob/main/README.zh-CN.md) · [Brand](https://github.com/hlang-tech/hlang/tree/main/media/brand)

hlang is an open-source flow-based programming language for TypeScript and JavaScript. A program is a graph of Readable, Transform, and Writable nodes. Nodes exchange data through named ports, and every port is an RxJS stream, so connections stay live while data flows.

A graph can be written in code, stored as JSON (`IGraph`), run in process by the interpreter, compiled ahead of time to an ES module, or built in a visual editor. The engine does not depend on any editor.

## Packages

| Package | Purpose |
| --- | --- |
| [`@hlang-org/runtime`](https://github.com/hlang-tech/hlang/tree/main/packages/runtime) | Nodes, ports, and flows on RxJS |
| [`@hlang-org/ir`](https://github.com/hlang-tech/hlang/tree/main/packages/ir) | `IGraph` types and `planGraph`, the front end shared by both backends |
| [`@hlang-org/interpreter`](https://github.com/hlang-tech/hlang/tree/main/packages/interpreter) | Run an `IGraph` in process, in Node.js or a browser |
| [`@hlang-org/compiler`](https://github.com/hlang-tech/hlang/tree/main/packages/compiler) | Compile an `IGraph` to a standalone ES module |
| [`@hlang-org/editor-core`](https://github.com/hlang-tech/hlang/tree/main/packages/editor-core) · [`editor-react`](https://github.com/hlang-tech/hlang/tree/main/packages/editor-react) · [`editor-ui`](https://github.com/hlang-tech/hlang/tree/main/packages/editor-ui) | Lumen, the node editor stack (0.x, in development) |

Every package is also published under the `@hlang-tech` scope with identical builds.

## Built on hlang

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://www.xiaoa.name/events/hlang-chinashop-2020/"><img src="https://raw.githubusercontent.com/hlang-tech/hlang/main/media/showcase/chinashop-2020.png" alt="A node development tool built on hlang" width="100%"></a>
      <p><b>Retail store operations</b><br><sub>Freshippo Rex · CHINASHOP 2020</sub></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/astack-tech/astack"><img src="https://raw.githubusercontent.com/hlang-tech/hlang/main/media/showcase/astack.png" alt="AStack" width="100%"></a>
      <p><b>AStack</b><br><sub>AI agents and workflows</sub></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/hlang-tech/hlang/tree/main/examples/editor-react-playground"><img src="https://raw.githubusercontent.com/hlang-tech/hlang/main/media/showcase/prism.png" alt="Prism, a node-based tool for image and video creators, built on Lumen" width="100%"></a>
      <p><b>Prism</b><br><sub>Image and video creation · in development</sub></p>
    </td>
  </tr>
</table>

## Start building

```sh
npm install @hlang-org/runtime @hlang-org/interpreter
```

Follow the [quick start](https://github.com/hlang-tech/hlang#quick-start) to write a graph in code, run it as data, and compile it.

## Contribute

hlang is [MIT licensed](https://github.com/hlang-tech/hlang/blob/main/LICENSE). Read the [contribution guide](https://github.com/hlang-tech/hlang/blob/main/.github/CONTRIBUTING.md) and open pull requests against `develop`. Report security problems privately through [security advisories](https://github.com/hlang-tech/hlang/security/advisories/new).

[Report an issue](https://github.com/hlang-tech/hlang/issues) · [Open a pull request](https://github.com/hlang-tech/hlang/pulls)
