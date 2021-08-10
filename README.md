# Django_user_management

Deployed on : Django rest api
Sample Data used : User Information Open json dataset

Access:
Input : JSON Post hit 
Sample Payloads:

# Returns all the data when empty json passed over the network:


Ex:http://serverip:8000/model/
Req type : POST
Payload data : {}

# Returns related data when all passed data matched to a record


Ex:http://serverip:8000/model/
Req type : POST
Payload data : {
    "email": "melany.wijngaard@example.com",
    "gender": "female",
    "birthdate": 608022796,
   "username": "bigpeacock217",
    "first_name": "melany",
    "last_name": "wijngaard"

  }

# Improvments:

1. Faster search, indexing, caching can be applied
2. Secutiry by binding IPs
3. Load Balancers can be applied for huge traffic
4. Deeplearning based model can be applied for string based search if there is a text corpus to search
5. Similarity based algorithms can be used
