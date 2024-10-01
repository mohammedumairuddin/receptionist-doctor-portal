# receptionist-doctor-portal
git clone https://github.com/your_username/receptionist_doctor_portal.git
rails new .
bundle add pg
rails db:setup
bundle add devise
rails generate devise:views
rails generate devise User
class User < ApplicationRecord
  # Devise configuration
  # ...

  enum role: { receptionist: 0, doctor: 1 }
end
rails generate model Patient name:string email:string phone:string
rails generate model Doctor name:string specialization:string
git add .
git commit -m "Initial commit"
git push origin main
