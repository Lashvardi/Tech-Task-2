# 🚗 RentCar API 🚀

API-შ შესაზლებლობები:

- 👀 გასაქირავებელი მანქანების დეტაულირი ინფორმაციის მოწოდება
- 🕵️ მანქანების გაფილტვრა
- 🔎 ხშირად გაქირავებული მანქანების მოწოდება.
- 💳 ქირაობა
- 🏷️ გასაქირავებლად დადება

## 🌐 Base URL 

API-ს გამოსაყენებლად მიმართეთ შემდეგ მისამართს [API-მისამართს](https://rentcar.webwide.ge/api).
<br>
```https://rentcar.webwide.ge/api```

## 🔑 Authentication

API იყენებს JWT (Json Web Token)-ს ავტორიზასიისთვის. 

შექმენით თქვენი მომხმარებელი ან გამოიყენეთ უკვე არსებული სატესტო მომხმარებელი. დეტალური ინფორმაცია არის მითითებული [API დოკუმენტაციაში](https://rentcar.webwide.ge/swagger/index.html).

## ⚙️ Endpoints

Endpoint-ების მიმოხილვა:

- **GET  &nbsp;&nbsp;&nbsp;api/cars**: დაგიბრუნებთ ინფორმაციას პირველი 20 მანქანის შესახებ.
- **GET  &nbsp;&nbsp;&nbsp;api/cars/{id}**: დაგიბრუნებთ ინფორმაციას კონკრეტული მანქანის შესახებ.
- **GET  &nbsp;&nbsp;&nbsp;api/cars/popular**: დაგიბრუნებთ ინფორმაციას პოპულარული მანქანების შესახებ.
- **POST &nbsp;api/Purchase/purchase**: იქირავებთ მანქანას.
- **POST &nbsp;api/cars/Car**: დაამატებს მანქანას გასაქირავებლად.~
- **POST &nbsp;api/Users/register**: დაარეგისტრირებს მომხმარებელს
- **POST &nbsp;api/users/login**: მომხმარებლის ავტორიზაცია

**დეტალური ინფორმაცია შეგიძლია ნახოთ დოკუმენტაციაში [API დოკუმენტაცია](https://rentcar.webwide.ge/swagger/index.html).**

## response-ის მაგალითი
```json
[
  {
    "id": 1,
    "brand": "Toyota",
    "model": "Corolla",
    "year": 2022,
    "imageUrl1": "https://example.com/images/car1.jpg",
    "imageUrl2": "https://example.com/images/car2.jpg",
    "imageUrl3": "https://example.com/images/car3.jpg",
    "image1": "car1.jpg",
    "image2": "car2.jpg",
    "image3": "car3.jpg",
    "price": 15000,
    "multiplier": 1.5,
    "capacity": 5,
    "transmission": "Automatic",
    "createdBy": "John Doe",
    "createdByEmail": "johndoe@example.com",
    "fuelCapacity": 50,
    "city": "New York",
    "latitude": 40.7128,
    "longitude": -74.0060,
    "ownerPhoneNumber": "+1234567890"
  }
]
```
## ❓ დაგჭირდათ დახმარება?
დახმარების შემთხვევაში დაუკვაშირდით მას ვინც მოგაწოდათ ეს დავალება.

წარმატებები ❤️
