academic <- data.frame(
  Student = c("A", "B", "C", "D", "E"),
  Math = c(85, 72, 90, 78, 88),
  Science = c(78, 85, 80, 75, 82),
  Attendance = c(95, 92, 98, 85, 93)
)

# 3D Scatter Plot
plot_ly(academic, x = ~Math, y = ~Attendance, z = ~Science, type = "scatter3d", mode = "markers")

# 3D Surface Plot
plot_ly(academic, x = ~Math, y = ~Attendance, z = ~Science, type = "mesh3d")

# Compare Science vs Math
plot_ly(academic, x = ~Math, y = ~Science, type = "scatter", mode = "lines+markers")

# Compare Science vs Attendance
plot_ly(academic, x = ~Attendance, y = ~Science, type = "scatter", mode = "lines+markers")


env <- data.frame(
  Location = c("A", "B", "C", "D", "E"),
  Temperature = c(15, 20, 18, 12, 17),
  Humidity = c(65, 70, 68, 60, 72),
  CO2 = c(400, 450, 420, 380, 430)
)

# 3D Scatter Plot
plot_ly(env, x = ~Temperature, y = ~Humidity, z = ~CO2, type = "scatter3d", mode = "markers")

# 3D Surface Plot
plot_ly(env, x = ~Temperature, y = ~Humidity, z = ~CO2, type = "mesh3d")

# Compare CO2 vs Temperature
plot_ly(env, x = ~Temperature, y = ~CO2, type = "scatter", mode = "lines+markers")

# Compare CO2 vs Humidity
plot_ly(env, x = ~Humidity, y = ~CO2, type = "scatter", mode = "lines+markers")

  Product = c("A", "B", "C", "D", "E"),
  Price = c(50, 70, 60, 45, 55),
  Rating = c(4.2, 3.8, 4.0, 4.5, 3.9),
  AgeGroup = c(30, 40, 20, 50, 30)  # Converted to numeric midpoint
)

# 3D Scatter Plot
plot_ly(survey, x = ~Price, y = ~AgeGroup, z = ~Rating, type = "scatter3d", mode = "markers")

# 3D Surface Plot
plot_ly(survey, x = ~Price, y = ~AgeGroup, z = ~Rating, type = "mesh3d")

# Compare Rating vs Price
plot_ly(survey, x = ~Price, y = ~Rating, type = "scatter", mode = "lines+markers")

# Compare Rating vs AgeGroup
plot_ly(survey, x = ~AgeGroup, y = ~Rating, type = "scatter", mode = "lines+markers")

