# Crudoperations-on-employeedata
How to Create, Delete,Get employee data
using FirstWeb.Api.Services.Interfaces;
using FirstWeb.Api.Models;
using system.Collections.Generic;

namespace FirstWeb.Api.Services
{
    public class EmployeeService : IemployeeService
    {
      //  Create 

      void CreateEmployee(Employee employee);

      // Read

      Employee GetEmployee(int id);

      Ienumerable<Employee>GetEmployee();

      //update
      void UpdateEmploee(Employee employee);

      // Delete
      bool DeleteEmployee(Employee employee);

    }
}
