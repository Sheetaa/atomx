# Atomx

[Atom](https://www.npmjs.com/package/vip-server-renderer)(not the editor) tools for VSCode.

## Features
- Snippets
- Syntax-highlighting

## Quick Start
Install [Atomx](https://marketplace.visualstudio.com/items?itemName=johnnyyao.atomx)

## Usage
1. create a file named `xxx.atom`;
2. write word `atom` or `template` and type `Tab`. Then, there's template code below:

    ```vue
    <template>
        
    </template>

    <script type="config">
    {
        props: {},
        data: {},
        components: {}
    }
    </script>

    <script type="php">
        function render(ctx) {
            return parent::render(ctx);
        }
    </script>

    <script>
    export default {
        mounted() {},
        methods: {}
    };
    </script>

    <style lang="less" scoped>
        
    </style>
    ```

3. other snippets include `atom:template`, `atom:config`, `atom:php`, `atom:js`, `atom:style`.
