
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   libftOps                                           :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: agaley <agaley@student.42lyon.fr>          +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2022/11/08 01:07:00 by agaley            #+#    #+#             */
/*   Updated: 2022/11/08 02:12:00 by agaley           ###   ########lyon.fr   */
/*                                                                            */
/* ************************************************************************** */

# libftOps - Test your libft

Create .github/workflows/test.yml with :

```yml
name: Test ftlib

on:
  push:
    branches: [main, master]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: unkn0wn107/libftOps@main
```

And enjoy continuous testing

Thanks to https://github.com/Tripouille/libftTester which does all the heavy lifting
