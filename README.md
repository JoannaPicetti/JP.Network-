# My Story 

https://www.jp.network/


I am Joanna from Buenos Aires. Latina from Argentina

I am a politician and activist, I stand for:

Human Rights

Children Rights

Women Rights

All the vulnerable and oppressed people: indigenous, black people, South Africans, refugees, Latinos, people discriminated by religion or ethnicity and LGTBQ

I am still in this fight trying to raise my voice to tell my story, but not only because is my story, but also because is the story of all of us. 

My aim is to empower them the give them skills and tools they need to rock the world, reboot the planet, and to create a new future together.

I am a Congresswoman, democratically elected in my Nation, but the power system pushed me away and prohibited me from holding the electoral office. (I am a little bit rebel and unmanageable, but I feel they did this because I am young and women and they did not imagine that I would win). When I won they began to torture and force me to prevent me from taking the position. They put me in a legal and judiciary Kafkanian battle and created court cases to harm me to this day. (You know, the politics is so hard, and dirty). Nevertheless, I couldn't stop to stand for my rights and for the rights of all the people who voted in this election. 

Climate Change & Activism
Right now I am an activist, I support young people because young people through climate change movement are the only ones who can transform this old, violent, and toxic social system. I am millennial and I fell more and more of our generation have to take the power, but with social consciousness, with a "green eye" and alike a “blue wave", we have to act now and take the power in all the stakeholders and change the system at once.
I am an expert in pressing POWER and push for radical, social, and political change to the toxic structures, systems, and cultures that exclude and marginalize vulnerable people.


Pressing Power / Tell the truth
I decided to rise my voice and speak up in the middle of the Argentinian Parliament because the president was lying, he was not telling the truth to the people.

I can not accept when the old fashioned politician have to lie to win votes. We need more people asking the power system and demanding that people in the power tell the truth.


Joanna Picetti Photo.jpg
From my LinkedIn profile
Actuary - Actuarial Science - Not finished
BBA - Bachelor of Administration, University of Buenos Aires (UBA)

MBA - Master in Business Administration (IAE Business School). She is currently finishing her second master’s degree, MPP - Master in Public Policy, (University of Georgetown). Since December 2015, she has worked in the Public Sector, Ministry of Interior and Housing of the Argentine Nation. Its political task is marked by the fight against injustice, and by the construction of an Open, participatory, collaborative and transparent Government. She was the CEO of Water Public Company in Argentine, (Aysa- Agua y Saneamientos de Argentina, S.A.) (2015-2017). Prior to this, her experience and professional career was carried out in the private sector for more than 10 years, occupying regional and global management positions in multinational firms. (2005-2015)

IMG_5910.jpg
Systemic Governance
The United Nations designed the SDGs as a clear path for the future of the world. The path to growth and prosperity for all, inspired by the SDGs we will focus the contents on specific areas in which, through technological innovations we can play a key role.

https://twitter.com/Joannapicetti/status/1281882887252578306

Joanna Picetti is Argentinian congresswoman on a mission to empower children and women in the global south and create a new model of democracy designed for 2020 and beyond…






Updating JP.network website


I am democratically elected member of the Argentine Congress.

The old corrupted power system pushed me away.

When this publication goes to print (August 2020) there are multiple ongoing legal threads. 

You can type my name (Joanna Picetti) into Google, just be aware of “Fake News”, be careful who you trust.

I am in Estonia to empower humanity and show the way in the face of adversity.

My massive transformative purpose is to create a Unified Global Government. 

The future of Governance is based on modern technology ( blockchain, AI, real-time data ) and I went to Estonia because Estonia is the flagship of the worlds first digital society. 

Every institution that we can see today in our world was created after WW2 (Bretton Woods financial system, United Nations, NATO). They are no longer fit for purpose, we need to change the way we operate as humanity. 

Unified Global Government is a big vision, that is why getting there in stages. 
Special Economic Zones is the direct path towards accomplishing this goal.

Simplifying global trade and adding blockchain trust and transparency can completely change how we do Business. 




enum Token { Personhood, Registration, Immigration }
mapping (uint => mapping (Token => mapping (address => uint))) public balanceOf;
mapping (uint => mapping (Token => mapping (address => mapping (address => uint)))) public allowed;
function _transfer(uint _t, address _from, address _to, uint _value, Token _token) internal {
require(balanceOf[_t][_token][_from] >= _value);
balanceOf[_t][_token][_from] -= _value;
balanceOf[_t][_token][_to] += _value;
}
function transfer(address _to, uint _value, Token _token) external {
_transfer(schedule(), msg.sender, _to, _value, _token);
}
function approve(address _spender, uint _value, Token _token) external {
allowed[schedule()][_token][msg.sender][_spender] = _value;
}
function transferFrom(address _from, address _to, uint _value, Token _token) external {
uint t = schedule();
require(allowed[t][_token][_from][msg.sender] >= _value);
_transfer(t, _from, _to, _value, _token);
allowed[t][_token][_from][msg.sender] -= _value;
}






