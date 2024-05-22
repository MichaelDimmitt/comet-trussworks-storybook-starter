# Install:
1. nvm use 18;
2. yarn install;
3. yarn run dev;

# Todo Items:
1. add react router
2. build pages.
3. network request pattern, possibly just useEffect({makeRequest}, []) + useCallback -  see link:  https://stackoverflow.com/a/53572588/5283424
4. folder structure: src/pages, src/utils, src/hooks, 
5. forms 
6. we should resist making new components, for speed. but if needed will eventually make it into a new storybook that we npm publish. which I can do on thursday pretty quickly.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
