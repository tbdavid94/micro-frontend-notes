# micro-frontend-notes
## All research notes for micro frontend with angular framework

Angular Elements: Angular Elements cho phép bạn tạo các component Angular dưới dạng các web components độc lập, có thể sử dụng trong bất kỳ framework nào hoặc thậm chí cả trong các trang HTML thuần túy. Điều này giúp bạn tạo ra các bundle nhỏ hơn và dễ tích hợp hơn vào các dự án khác. Bạn có thể sử dụng Angular Elements để xây dựng và đóng gói một component Angular thành một bundle độc lập.

Webpack hoặc Rollup: Bạn cũng có thể sử dụng các công cụ như Webpack hoặc Rollup để đóng gói các component Angular của mình thành các bundle JavaScript. Tuy nhiên, việc cấu hình và tích hợp có thể phức tạp hơn so với việc sử dụng công cụ như ng-packagr hoặc Angular Elements.

Module Federation (trong Webpack 5+): Nếu bạn đang làm việc với Webpack 5 hoặc mới hơn, Module Federation có thể là một phương pháp hữu ích để chia sẻ các module giữa các ứng dụng. Bạn có thể sử dụng Module Federation để chia sẻ component Angular từ một ứng dụng sang các ứng dụng khác một cách linh hoạt.