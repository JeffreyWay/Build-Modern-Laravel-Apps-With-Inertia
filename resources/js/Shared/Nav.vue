<template>
  <nav>
    <ul class="flex list-disc space-x-4 list-inside">
      <li>
        <NavLink href="/" :active="$page.component === 'Home'">
          Home
        </NavLink>
      </li>

      <li>
        <NavLink href="/users" :active="$page.component === 'Users'">
          Users
        </NavLink>
      </li>

      <li>
        <NavLink href="/settings" :active="$page.component === 'Settings'">
          Settings
        </NavLink>
      </li>
    </ul>
  </nav>
</template>

<script>
import NavLink from "./NavLink";

export default {
  components: { NavLink },
};
</script>
