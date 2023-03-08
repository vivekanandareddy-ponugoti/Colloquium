# Computer Security and privacy(APECS):

## Edge Computing(not Cloud Computing):
There are mainly two services provided by cloud (Computing power, Storage). The edge computing became important because the connections between devices are rapidly increasing like apple eco system. These devices generate data and this data needs to be processed. This required huge amount of data. Using edge computing will remove most of these problems.

## APplications on edge computing:
Key perticulaRrfeatures. Smart IOT devices(cameras etc). The processing should be happned closed to the vehicle(Low latency, Aggregation, Privacy). Local data is in the hands of users and can be deleted locally without letting anything go out. 

## Different architectures of edge computing:
MEC, MCC, Fog Computing, Cloudlet

## The Prevasive Edge Computing:
Contains Edge computing and IOT as internal dependency and cloud is considered to be external dependency

## PEC Advantages:
Multi stakeholder nature, Highly dynamic member pools, High device heterogenecity
Edge computing provide -> Software applicaation provider, Actual devices(IOT)

## Security and privacy challenges in PEC:
Verifiable computing, Confidential computing, Privacy preserving AI @ Edge, Access Control

## Dr. Tourani system model:
- Service Providers:
1. Static Services - Web-content, Multimedia Content
2. Dynamic services - Image anotation, Video analysis

- Cloud Computing providers:
1. AWS
2. Azure etc.

Communication between service and cloud is done by utilizing AIA. 

AIA is the route of trust(Consumer to base station and in between service provider and cloud providers). provides with encryption to ensure security of users, service providers data.

Edge computing comes into play by communicating with Cloud services to process data and client uses the service provder to have the service.
Here the malicious threat can be happned in the places of edge computing(Spoofing attacl to obtain user data) and even client itself as the client might have the intention of using the service without paying for it(By usign forged, shared, expired and no credentials).

## APECS rely on:
1. Access Token
2. Digital signature
3. Attribute based encryption(Asementric -  is awfully slow)

Access Token - 5 Tuple with provider unique identifier, User certification, Token Expiry time respectively

Syntax - T = <IDp,[IDs], Certu, [Lu], Texp>

## Process of AWECS uses JWT :
user- Service registration with username and password, A access token(JWT)

After the token is verified the user is signed in, request is received, service is provided.

## ABE(Attribute based encryption):
The attributes are used to determine who can decrypt a certain data where a user cannot access change data which has write acess only for the owner.

- Process is Asyncronous(Complex and time consuming):
Setup -> Key Generation -> Encryption -> Decryption

To resolve these slow processes user encrypts the data in an asymmetric manner and make this symmetric data to be attribute based encyption.

## APECS uses MABE to guarantee authenticity of edge servers for dynamic services:
User - base station - edge servers - cloud

- Process model on mobile

APECS PKC uses TLS for authentication and edge server tokens to establish edge server authorization:

Comparision between compacy edge, hand held, Desktop. Desktp is most powerful as it took least amount of time.

Using which process for which depends on the process where realtime analysis requires fastest computation process.

## Deployed APCS on the GENI testbed
 On mobile

