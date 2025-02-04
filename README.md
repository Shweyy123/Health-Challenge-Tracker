
# **Health Tracker**  

A web application built with Angular to track users' workout progress and related activities.

## **Project Structure**  

```
public/
│── logo.png
src/
│── app/
│   ├── components/
│   │   ├── add-user/
│   │   ├── progress-chart/
│   │   ├── users/
│   ├── services/
│   │   ├── add-user/
│   │   ├── chart/
│   │   ├── dialog/
│   ├── app.component.ts
│   ├── app.config.ts
│   ├── app.model.ts
│   ├── app.routes.ts
│── index.html
│── main.ts
│── styles.css
│── ...
```

## **Installation & Setup**  

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/health-tracker.git
   cd health-tracker
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   ng serve
   ```

4. Open the application in your browser:
   ```
   http://localhost:4200
   ```

## **Features**  

✅ **User Management** – Add, update, and manage users.  
📊 **Progress Tracking** – Visualize workout progress with charts.  
💬 **Dialog Service** – Interactive dialogs for user interactions.  

## **Built With**  

- **Angular** - Frontend framework  
- **Tailwind CSS** - Styling  
- **RxJS** - Reactive programming  
- **Angular Material** *(if used)*  

## **Configuration**  

- Tailwind CSS is configured in `tailwind.config.js`.  
- Routes are defined in `app.routes.ts`.  

## **Troubleshooting**  

If you encounter any issues:  
1. Make sure you have **Node.js** installed (`node -v`).  
2. Run `npm install` to ensure all dependencies are installed.  
3. Clear cache and reinstall:  
   ```sh
   rm -rf node_modules package-lock.json  
   npm cache clean --force  
   npm install  
   ```

## **Screenshots**  

### **1. Workout Entry Form**  
Users can input details like **User Name**, **Workout Type**, and **Workout Minutes**.  


![Workout Entry Form](https://github.com/user-attachments/assets/b222e00f-7e9c-4d08-9091-4231b9b7e329)  

### **2. User Workout List**  
- Displays all recorded workouts  
- Includes **search**, **filter**, and **pagination** functionalities

  ![User Workout List](https://github.com/user-attachments/assets/628a257d-b447-46b8-ba63-e703d276e0a1)  

### **3. Workout Progress Visualization (Charts)**  
(Optional Feature) Users can see **progress insights** using graphical charts.  

![Workout Progress Chart](https://github.com/user-attachments/assets/73e1d626-c5cb-4499-b06b-fe54258b25f8)  

---



