# Cronexia / Test NextJs + Chakra UI

yep

[doc](https://nextjs.org/docs/app/getting-started/installation)

```bash
npx create-next-app@latest
cd project/
bun dev
```

doc [chakra](https://www.chakra-ui.com/docs/get-started/frameworks/next-app)

```bash
bun add @chakra-ui/react @emotion/react @chakra-ui/cli@3.3.1

npx @chakra-ui/cli snippet add
```

Update tsconfig

```ts
{
  "compilerOptions": {
    "target": "ESNext",
    "module": "ESNext",
    "moduleResolution": "Bundler",
    "skipLibCheck": true,
    "paths": {
      "@/*": ["./src/*"]
    }
  }
}
```

Setup provider > app/layout.tsx

done

Optimize Bundle

done

Enjoy

Ajout de l'exemple

```bash
bun dev
```

Ajout autre compo

[accordeon](https://www.chakra-ui.com/docs/components/accordion)

```bash
npx @chakra-ui/cli snippet add accordion
```

puis ajout dans page.tsx
