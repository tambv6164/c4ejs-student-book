``` javascript
    {
        let y = 30;
        {
            let x = 20;
        }
        console.log(x);
    }
```

Trong đoạn code trên, chương trình sẽ báo lỗi. Vì biến x được khai báo với **let**. Biến được tạo ra bởi **let** chỉ có thể truy cập được trong **Scope** bao quanh nó. Câu lệnh cuối cùng ( console.log(x) ) nằm ngoài **Scope** của biến x nên không thể in ra x.