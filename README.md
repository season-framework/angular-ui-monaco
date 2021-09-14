## Angularjs UI Monaco Editor

- monaco editor for `angularjs 1.x.x`

## Usage

- import monaco loader

  ```html
  <script src="<monaco-dir>/monaco/min/vs/loader.js"></script>
  ```

- angular controller scope

  ```html
  <div ng-controller="your-ctrl">
    <div ng-model="code" ui-monaco-opts="{'language': 'javascript', 'automaticLayout': true}" ui-monaco)
  </div>
  ```
