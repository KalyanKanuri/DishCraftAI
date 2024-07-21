
```
DishCraftAI
├─ backend
│  ├─ .dockerfile
│  ├─ agents
│  │  ├─ analyzer
│  │  │  ├─ ingredient_analyzer.py
│  │  │  └─ __init__.py
│  │  ├─ designer
│  │  │  ├─ recipe_designer.py
│  │  │  └─ __init__.py
│  │  ├─ nlp
│  │  │  ├─ nlp_model.py
│  │  │  └─ __init__.py
│  │  ├─ utils
│  │  │  ├─ text_processer.py
│  │  │  ├─ vector_operator.py
│  │  │  └─ __init__.py
│  │  └─ __init__.py
│  ├─ app
│  │  ├─ api
│  │  │  ├─ controllers
│  │  │  │  ├─ recipie_controller.py
│  │  │  │  └─ user_controller.py
│  │  │  ├─ dependencies.py
│  │  │  ├─ __init__.py
│  │  │  └─ __pycache__
│  │  │     └─ __init__.cpython-312.pyc
│  │  ├─ core
│  │  │  ├─ config.py
│  │  │  ├─ security.py
│  │  │  └─ __init__.py
│  │  ├─ crud
│  │  │  ├─ base.py
│  │  │  ├─ crud_recipe.py
│  │  │  ├─ crud_user.py
│  │  │  └─ __init__.py
│  │  ├─ database.py
│  │  ├─ main.py
│  │  ├─ models
│  │  │  └─ __init__.py
│  │  ├─ schemas
│  │  │  ├─ recipe_schema.py
│  │  │  ├─ user_schema.py
│  │  │  └─ __init__.py
│  │  ├─ services
│  │  │  ├─ email_service.py
│  │  │  └─ __init__.py
│  │  ├─ __init__.py
│  │  └─ __pycache__
│  │     └─ main.cpython-312.pyc
│  ├─ infrastructure
│  │  ├─ middleware.py
│  │  ├─ security.py
│  │  └─ __init__.py
│  ├─ requirements.txt
│  ├─ tests
│  │  ├─ api_tester.py
│  │  ├─ conftest.py
│  │  ├─ test_agents
│  │  │  └─ test_recipe_designer.py
│  │  └─ test_api
│  │     └─ recipy_tester.py
│  └─ __init__.py
├─ frontend
│  ├─ .eslintrc.cjs
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ postcss.config.js
│  ├─ public
│  │  └─ vite.svg
│  ├─ README.md
│  ├─ src
│  │  ├─ App.css
│  │  ├─ App.tsx
│  │  ├─ assets
│  │  │  ├─ images
│  │  │  │  └─ chef_logo.jpeg
│  │  │  └─ react.svg
│  │  ├─ components
│  │  │  ├─ agents
│  │  │  ├─ common
│  │  │  │  └─ Header.tsx
│  │  │  └─ recipes
│  │  ├─ context
│  │  │  └─ AuthContext.ts
│  │  ├─ index.css
│  │  ├─ main.tsx
│  │  ├─ pages
│  │  ├─ services
│  │  │  └─ api
│  │  │     ├─ recipe_controller.ts
│  │  │     └─ user_controller.ts
│  │  ├─ types
│  │  │  ├─ recipe_type.ts
│  │  │  └─ user_type.ts
│  │  ├─ utils
│  │  │  ├─ constants.ts
│  │  │  └─ helpers.ts
│  │  └─ vite-env.d.ts
│  ├─ tailwind.config.js
│  ├─ tsconfig.app.json
│  ├─ tsconfig.json
│  ├─ tsconfig.node.json
│  └─ vite.config.ts
├─ .gitignore
├─ .hintrc
├─ docker-compose.yml
└─ README.md
```