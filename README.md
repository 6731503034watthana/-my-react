# -my-react

# เทอร์มินัล A (backend)
cd ~/workspaces/-my-react/bmi-app/backend
mvn -q clean package
mvn spring-boot:run
ควรเห็น Tomcat started on port(s): 8080.

เทส API ให้รู้เรื่อง:

bash
Copy code
curl -s -X POST http://localhost:8080/api/bmi \
  -H "Content-Type: application/json" \
  -d '{"weightKg":70,"heightCm":170}'
เปิดฝั่ง React ให้เชื่อมครบวงจร
bash
Copy code
# เทอร์มินัล B (frontend)
cd ~/workspaces/-my-react/bmi-app/frontend
npm install   # ครั้งแรกเท่านั้น
npm run dev -- --hosttest push Wed Oct 15 04:45:24 UTC 2025
test push Wed Oct 15 04:46:27 UTC 2025
