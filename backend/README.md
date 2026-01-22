backend/
 ├─ package.json
 ├─ server.js
 ├─ .env   (Render पर env variables में डालोगे)
 ├─ config/
 │   └─ cloudinary.js
 ├─ controllers/
 │   ├─ adminController.js
 │   ├─ authController.js
 │   ├─ couponController.js
 │   ├─ orderController.js
 │   ├─ otpController.js
 │   ├─ productController.js
 │   ├─ returnController.js
 │   ├─ sellerController.js
 │   ├─ sellerOrdersController.js
 │   └─ addressController.js
 ├─ middleware/
 │   ├─ authMiddleware.js
 │   └─ roleMiddleware.js
 ├─ models/
 │   ├─ User.js
 │   ├─ Product.js
 │   ├─ Order.js
 │   ├─ Coupon.js
 │   ├─ Otp.js
 │   └─ Address.js
 ├─ routes/
 │   ├─ adminRoutes.js
 │   ├─ authRoutes.js
 │   ├─ couponRoutes.js
 │   ├─ orderRoutes.js
 │   ├─ otpRoutes.js
 │   ├─ paymentRoutes.js
 │   ├─ productRoutes.js
 │   ├─ returnRoutes.js
 │   ├─ sellerRoutes.js
 │   ├─ sellerOrdersRoutes.js
 │   ├─ uploadRoutes.js
 │   └─ addressRoutes.js
 └─ utils/
     └─ sendEmail.js
