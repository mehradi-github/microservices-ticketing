# Microservices with Node JS and React
- [Microservices with Node JS and React](#microservices-with-node-js-and-react)
  - [Adding a Submodule](#adding-a-submodule)
  
## Adding a Submodule

```sh

git submodule add https://github.com/<user>/microservices-ticketing-auth auth
# Newer versions of Git will do this automatically, but older versions will require you to explicitly tell Git to download the contents of submodule
git submodule update --init --recursive
# Clone command to ensure you download everything, including any submodules
git clone --recursive <project url>


```