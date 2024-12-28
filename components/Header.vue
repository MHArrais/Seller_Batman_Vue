<template>
    <div>
      <header>
        <a>
          <img id="logo" src="@/assets/logo.png" alt="logo">
        </a>
        <nav>
          <ul>
            <!-- Usando NuxtLink para navegação -->
            <li>
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/contato">Contatos</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/fotos">Fotos</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/comentario">Comentário</NuxtLink>
            </li>
          </ul>
        </nav>
      </header>
    </div>
  </template>
  
  <style scoped>
  /* Remove a cor padrão e o sublinhado dos links */
  nav a,
  nav li a {
    text-decoration: none; /* Remove o sublinhado padrão */
    color: inherit; /* Herda a cor do elemento pai ou defina uma cor personalizada */
  }
  
  /* Estilo quando o link está ativo */
  nav .nuxt-link-active {
    color: #000; /* Defina a cor desejada para o link ativo */
    font-weight: bold; /* Opcional: para destacar o link ativo */
  }
  
  /* Definindo uma cor de hover personalizada */
  nav a:hover {
    color: #007bff; /* Alterar para a cor de hover desejada */
  }
  </style>
  