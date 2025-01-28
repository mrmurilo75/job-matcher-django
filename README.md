# job-matcher-django

A simple service that matches candidate profiles with open positions.

# Roadmap

1. A Django REST API that receives the cadidates curriculum as PDF, and extracts the information from it, saving the extracted information to the database. For separation of concerns, there'll be an accessible service which receives the relevant data. Focusing on the IT sector: define known languages and skill levels, same for technologies, and finally for principles (for example OOP, Data, Web, Testing, etc). Some more subject topics can be added by keyword, such as 'leadership', 'sales', etc.
2. A Django REST API that receives jobs listing, as text or md, and extracts the relevant information from it. Same as the above, there'll be a separate service accessible that can directly receive the information and another service that can receive an url to be crawled.
3. Lastly, the cross-referencing of candidates and open positions.

After this, we'll worry about containerization, deployment, and other technical issues.
