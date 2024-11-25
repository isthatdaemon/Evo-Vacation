# Vacation Day Calculator 🗓️  

A React-based web application for calculating vacation compensation for shift-based employees using their worked hours, salaries, justified absence days, and vacation days.

## 🚀 Features  
- **Dynamic Inputs**: Enter hours, salaries, and absence days to calculate compensation.  
- **Accurate Formula**: Uses `Vacation Compensation = A * (B / C) * Vacation Days`.  
  - `A`: Average daily worked hours.  
  - `B`: Total salary for worked hours (excluding overtime).  
  - `C`: Total worked hours (excluding overtime).  
- **Responsive & Intuitive UI**: Designed for both desktop and mobile users.  

## 🛠️ Tech Stack  
- **Frontend**: React.js  
- **Styling**: CSS  

## 📦 Installation  
1. Clone the repository:  
   `git clone https://github.com/isthatdaemon/Evo-Vacation.git`  
2. Navigate to the folder:  
   `cd Evo-Vacation`  
3. Install dependencies:  
   `npm install`  
4. Start the development server:  
   `npm start`  
5. Open: [http://localhost:3000](http://localhost:3000)  

## 📝 Usage  
1. Enter **Worked Hours** (e.g., `120,160,80`), **Salaries** (e.g., `1000,1500,800`), **Absence Days**, and **Vacation Days**.  
2. Press **Calculate** to view results.  

## 🧮 Example  
Given:  
- Worked Hours: `120, 160, 80`  
- Salaries: `1000, 1500, 800`  
- Absence Days: `0`  
- Vacation Days: `5`  

Steps:  
1. `A = (120 + 160 + 80) / (60 - 0) = 6`  
2. `B = 1000 + 1500 + 800 = 3300`  
3. `C = 120 + 160 + 80 = 360`  
4. `Compensation = A * (B / C) * Vacation Days = 6 * (3300 / 360) * 5 = 273 GEL`  

## 🤝 Contributing  
1. Fork the repo.  
2. Create a new branch: `git checkout -b feature-name`.  
3. Commit changes: `git commit -m "Add feature"`.  
4. Push: `git push origin feature-name`.  
5. Submit a pull request.  

## 📜 License  
Licensed under the [MIT License](LICENSE).  

## 🌟 Acknowledgments  
Thanks to all contributors for their support and ideas!
