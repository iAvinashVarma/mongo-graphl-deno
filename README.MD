# GraphQL Server with Deno and MongoDB

* Sample GraphQL Server with Deno and MongoDB

# Deno Installation

```bash
$ curl -fsSL https://deno.land/x/install/install.sh | sh
```

* Add below lines in .bashrc

```vim
export DENO_INSTALL="/$HOME/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"
```

* Run the following command

```bash
$ source ~/.bashrc
```

# Deno Commands

* Run the project

```bash
$ deno run --allow-net server.ts
```

## Deno Links

* [Deno Land](https://deno.land/)
* [Deno Third Party Modules](https://deno.land/x)

## Modules Used

* [oak_graphql](https://deno.land/x/oak_graphql@0.6.1)

## GraphQL Query

```graphql
# Write your query or mutation here
{
  getUser(id: "Avi"){
    firstName,
    lastName
  }
}
```

## Notes

> Oak framework in Deno is general equivalent of Express in Node.
