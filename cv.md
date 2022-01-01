# German Bilalov

## Junior JavaScript Web Developer

## My Contact Info

-   **Address**: Karaganda, Kazakhstan
-   **Phone**: +7 708 950 80 50
-   **E-mail**: pinncho@gmail.com
-   **GitHub**: [unpin](https://github.com/unpin)

## Skills

-   HTML
-   CSS
-   JavaScript
-   Java 8 SE
-   React
-   Vue
-   Deno
-   Node.js
-   NestJS
-   NextJS
-   MongoDB
-   MySQL
-   Git
-   Typescript
-   Mongoose
-   Express.js
-   Webpack
-   Electron
-   GraphQL
-   Docker
-   Three.js
-   Figma
-   Adobe XD

## Code Snippet

```javascript
function findPermutations(string) {
    if (string.length === 1) return string;

    const output = [];

    for (let i = 0; i < string.length; i++) {
        const char = string[i];
        const rest = string.slice(0, i).concat(string.slice(i + 1));
        const perms = permutate(rest);
        for (const perm of perms) {
            output.push(char + perm);
        }
    }

    return output;
}
```

## Education

-   **College**:
    -   College of Engineering
-   **Courses**
    -   Java Web Development at [EPAM Systems](http://www.epam.com/)
    -   NodeJS at [Rolling School](https://rs.school/)

## Experience

-   2013-2014 - Web Designer

## Languages

-   Russian (Native)
-   English (C1) according to the British Council Test
-   Deutsch (B1)
