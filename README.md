# springboot-graphql

1、访问地址http://localhost:8080/graphql

2、请求

第一种使用postman选择body中的GraphQL

第二种使用安装官方的 GraphQL Playground

请求参数：
query {
  bookById(id: "book-1") {
    id
    name
    pageCount
    author {
      id
      firstName
      lastName
    }
  }
}

3、查看gradle中的gradle-wrapper.properties ->> distributionUrl的版本，最好使用当前环境版本大于版本
