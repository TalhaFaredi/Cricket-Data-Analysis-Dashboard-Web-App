
```markdown
# Cricket World Cup Analysis

![image](https://github.com/user-attachments/assets/f20edaae-55a7-4848-8dfd-e3e69b93c055)

## Overview
The **Cricket World Cup Analysis** application is designed to provide insights into the performance of cricket teams in One Day International (ODI) matches. Utilizing data visualization techniques, this app allows users to analyze team performance, match outcomes, and toss results through an interactive interface.

## Features
- **Team Performance Analysis**: Select a team and view statistics such as matches played, matches won, and performance based on toss outcomes.
- **Opposing Team Comparison**: Analyze match outcomes between two selected teams, including wins when batting or bowling first.
- **Venue Performance**: Explore match results at specific venues between two teams.
- **Toss Analysis**: Visualize the frequency of toss wins and how they correlate with match outcomes.
- **Interactive Visualizations**: Utilize Plotly and Seaborn for dynamic charts and graphs that present data in a visually appealing manner.

## Technologies Used
- **Streamlit**: For creating the web application interface.
- **Pandas**: For data manipulation and analysis.
- **Plotly Express**: For creating interactive visualizations.
- **Seaborn**: For statistical data visualization.
- **Python**: The primary programming language used.

## Installation
To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/cricket-analysis.git
   cd cricket-analysis
   ```

2. **Create a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the Dataset**: Ensure you have the `ODI_Match_info.csv` dataset in the project directory.

## Usage
1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Interact with the Application**:
   - Use the sidebar to select your desired team and analyze its performance.
   - Compare the performance of your team against another team.
   - Analyze match results based on specific venues and toss outcomes.

3. **Explore Results**:
   - Visual representations of the data will help in understanding trends and patterns.

## Screenshots
![image](https://github.com/user-attachments/assets/8d361b86-177d-4b8e-b742-8808f86be4e2)
![image](https://github.com/user-attachments/assets/0237bde4-54c1-47f2-9ec6-98bce3504712)


## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to the cricket data providers for making the ODI match data available.
- Inspiration and guidance from the data visualization community.

## Contact
For any questions or feedback, feel free to reach out at [your.email@example.com](mailto:your.email@example.com).

```

