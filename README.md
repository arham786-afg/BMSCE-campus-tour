# BMSCE-campus-tour
Giving a tour a BMS college of engineering



#include<iostream>
#include<string>
#include<cstdio>
#include<fstream>
#include <bits/stdc++.h>
using namespace std;

class modules{
    public:
    void bmsce(void){
        cout<<"*********************************************************WELCOME TO BMSCE***************************************************************************"<<endl;
        cout<<endl;       
        cout<<"Founded in 1946, BMS College of Engineering (popularly known as BMSCE) is located in Bengaluru, Karnataka. BMS College of Engineering is accredited\nby National Assessment and Accreditation Council (NAAC) with A++ grade and CGPA of 3.83 on a scale of four.\nCurrently, the institute is offering 13 undergraduate and 16 postgraduate courses in conventional and emerging areas.\nA total of 5,000 students are actively pursuing their higher studies and 350 research scholars are pursuing PhD degrees in BMSCE"<<endl;
        cout<<endl;
        cout<<"1.Courses offered."<<endl;
        cout<<"2.Eligibility."<<endl;
        cout<<"3.Placement details. "<<endl;
        cout<<"4.College details. "<<endl;
    }
    void courses_module(void);
    void eligibility_module();
    void placement_module();
    void contact_module();
};

class con_det:private modules{
    public:
    void contact();
};

 void modules::courses_module(void){
    cout<<"These are the course offered in the BMS college of Engineering"<<endl;
    cout<<"1.  Computer science"<<endl;
    cout<<"2.  Information science"<<endl;
    cout<<"3.  Electronics and Communication"<<endl;
    cout<<"4.  Electrical and Electronics"<<endl;
    cout<<"5.  Electronics and Telecommunication"<<endl;
    cout<<"6.  Electronics and Instrumentation"<<endl;
    cout<<"7.  Bio-technology "<<endl;
    cout<<"8.  Medical Electronics"<<endl;
    cout<<"9.  Aero-Space"<<endl;
    cout<<"10. Mechanical"<<endl;
    cout<<"11. Civil"<<endl;
    cout<<"12. Artificial intelligence and Machine Learning"<<endl;
    cout<<"13. Chemical "<<endl;
    cout<<"14. Industrial and Management "<<endl;

    cout<<endl;
    cout<<"Enter the branch details you want to know: ";
    int x;
    cin>>x;
    if(x==1){
        cout<<"Number of seats available in Computer Science are: 180 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. UMADEVI V"<<endl;
        cout<<"Email: umadevi.cse@bmsce.ac.in"<<endl;
    }
    if(x==2){
       cout<<"Number of seats available in Information Science are: 180 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. M DAKSHAYINI"<<endl;
        cout<<"Email: dakshayini.ise@bmsce.ac.in"<<endl; 
    }
      if(x==3){
       cout<<"Number of seats available in Electronics and Communication are: 180 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. ARATHI R SHANKAR"<<endl;
        cout<<"Email: arathi.ece@bmsce.ac.in"<<endl; 
    }
     if(x==4){
       cout<<"Number of seats available in Electrical and Electronics  are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr C. LAKSHMINARAYANA"<<endl;
        cout<<"Email: lngp.eee@bmsce.ac.in"<<endl; 
    }
    if(x==5){
       cout<<"Number of seats available in Electronics and Telecommunication are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. KANMANI BUDDHI"<<endl;
        cout<<"Email: bkanmani.tce@bmsce.ac.in"<<endl; 
    }
    if(x==6){
       cout<<"Number of seats available in Electronics and Instrumentation are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. KANMANI BUDDHI"<<endl;
        cout<<"Email: bkanmani.tce@bmsce.ac.in"<<endl; 
    }
    if(x==7){
       cout<<"Number of seats available in Bio-technology are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. Divijendra Nathan Reddy"<<endl;
        cout<<"Email: divijendranathr.bt@bmsce.ac.in"<<endl; 
    }
    if(x==8){
       cout<<"Number of seats available in Medical Electronics are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. VIJAYALAKSHMI.K"<<endl;
        cout<<"Email: Kv.ml@bmsce.ac.in"<<endl; 
    }
       if(x==9){
       cout<<"Number of seats available in Aero-space are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. Rammoahn Y S"<<endl;
        cout<<"Email: ysrmohan.aer@bmsce.ac.in"<<endl; 
    }
      if(x==10){
       cout<<"Number of seats available in Mechanical are: 180 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. RUDRA NAIK"<<endl;
        cout<<"Email: rudranaik.mech@bmsce.ac.in"<<endl; 
    }
    if(x==11){
       cout<<"Number of seats available in Civil are: 180 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. PRASANNA KUMAR P."<<endl;
        cout<<"Email: ppk.civ@bmsce.ac.in"<<endl; 
    }
    if(x==12){
       cout<<"Number of seats available in Artificial Intelligence and Machine Learning are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. GOWRISHANKAR"<<endl;
        cout<<"Email: gowrishankar.cse@bmsce.ac.in"<<endl; 
    }
    if(x==13){
       cout<<"Number of seats available in Chemical are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. C T PUTTASWAMY"<<endl;
        cout<<"Email: puttaswamyct.che@bmsce.ac.in"<<endl; 
    }
    if(x==14){
       cout<<"Number of seats available in Industrial and Management are: 60 "<<endl;
        cout<<endl;
        cout<<"Contact Details of HOD "<<endl;
        cout<<"Name: Dr. B. RAMESH NAYAK"<<endl;
        cout<<"Email: brnayak.iem@bmsce.ac.in"<<endl; 
    }




}
 void modules :: eligibility_module(){
    long long int rank;
    long long int phone;
     string name , lastname; 
     int x;
     int y=1;
    cout << "Enter your First Name " << endl;
    cin >>name ;
    cout << "Enter your last Name" << endl;
    cin >> lastname;
    
    ofstream myfile( lastname ,ios::app);
    myfile<<name;
    myfile << lastname << endl;
    fflush(stdout); 
     cout << "Enter your phone number" << endl;
    cin >> phone;
    myfile << phone << endl;
    cout << "please enter your rank" << endl;
    cin >> rank ;
    myfile << rank << endl;
     myfile.close();
    fflush(stdout);
    if(rank<=600)
    {
        x=1;
    }
    else if (rank<=894)
    {
        x=2;
    }
    else if (rank<=1403)
    {
        x=3;
    }
    else if (rank<=4921)
    {
        x=4;
    }
    else if (rank<=5000)
    {
        x=5;
    }
    else if (rank<=5763)
    {
        x=6;
    }
    else if (rank<=6362)
    {
        x=7;
    }
    else if (rank<=9935)
    {
        x=8;
    }
    else if (rank<=10023)
    {
        x=9;
    }
    else if (rank<=16687)
    {
        x=10;
    }
    else if (rank<=22315)
    {
        x=11;
    }
    else if (rank > 22315)
    {
        x=0;
    }
    cout << "your eligible for"<< endl;
    
  switch (x)
  {
  case 1: cout <<y <<")BE Computer Science and Engineering"<<endl ; y++;  
  case 2: cout <<y <<")BE Information Science & Engineering"<<endl; y++; 
  case 3: cout <<y <<")BE Electronics & Communication Engineering"<<endl ; y++; 
  case 4: cout <<y <<")BE Aerospace Engineering"<<endl; y++;
  case 5: cout <<y <<")BE Telecommunication Engineering"<<endl ; y++;
  case 6: cout <<y <<")BE Biotechnology"<<endl; y++;
  case 7: cout <<y <<")BE Electronics and Instrumentation Engineering"<<endl ; y++;
  case 8: cout <<y <<")BE Mechanical Engineering"<<endl ; y++;
  case 9: cout <<y <<")BE Chemical Engineering"<<endl ; y++;
  case 10: cout <<y <<")BE Electronics and Instrumentation Engineering"<<endl; y++;
  case 11: cout <<y <<")BE Medical Electronics"<<endl; y++;break;
  
  default:
  cout << "Non of the courses provided by BMSCE" << endl;
      break;
  }

 }
 void modules::placement_module(void){

     cout<<"placement details:"<<endl;
     cout<<"1.placement details of last 5 years."<<endl;
     cout<<"2.internship details of last 5 years."<<endl;
     cout<<"3.placement percentage."<<endl;

    cout<<endl<<"enter the placement detail you want to check"<<endl;
    int h;
    cin>>h;
    if(h==1){
     cout<<endl<<endl<<"Placement Details of last 5 Years:"<<endl<<endl;
     long int year[5]={2017,2018,2019,2020,2021};
     long int stud_no[5]={958,1078,946,1005,1059};

     cout.width(5);
     cout<<"YEAR";
     cout.width(25);
     cout<<"NO OF STUDENTS PLACED"<<endl<<endl;

    for(int i=0;i<5;i++){

        cout.width(5);
        cout<<year[i];

        cout.width(15);
        cout<<stud_no[i]<<endl;

    }}

    else if(h==2){
    cout<<endl<<"Internship Details of Last 5 Year"<<endl<<endl;
    long int year1[5]={2017,2018,2019,2020,2021};
     long int stud_noo[5]={149,270,242,555,591};

     cout.width(5);
     cout<<"YEAR";
     cout.width(30);
     cout<<"NO OF STUDENTS INTERNED:"<<endl<<endl;

    for(int i=0;i<5;i++){

        cout.width(5);
        cout<<year1[i];

        cout.width(18);
        cout<<stud_noo[i]<<endl;

    }}

    else if(h==3){
        cout<<endl<<"placement percentage of Last 5 Year:"<<endl<<endl;

     long int year2[5]={2017,2018,2019,2020,2021};
     long int stud_nooo[5]={958,1078,946,1005,1059};
     long int stud_yes[5]={1000,1100,960,1007,1110};
     float per[5]={95.80,98.00,98.54,99.80,95.40};

     

     cout.width(5);
     cout<<"YEAR";
     cout.width(30);
     cout<<"NO OF STUDENT REGISTERED";
     cout.width(30);
     cout<<"NO OF STUDENT PLACED";

     cout.width(30);
     cout<<"PLACEMENT PERCENTAGE(%)"<<endl<<endl;


    
    for(int i=0;i<5;i++){

        cout.width(5);
        cout<<year2[i];

        cout.width(18);
        cout<<stud_yes[i];

        cout.width(32);
        cout<<stud_nooo[i];

         cout.width(34);
         cout.precision(5);
        cout<<per[i]<<endl;
        
      
    }
    }
    else{
    cout<<"enter correct option"<<endl;
    }

 }
 void modules::contact_module(void){
     cout<<"Dr.S.Muralidhara "<<endl<<"Principal"<<endl<<"080 22427424, 080 26614357"<<endl<<"principal@bmsce.ac.in"<<endl;
 }

void con_det:: contact(){
    cout<<"CONTACT DETAILS:"<<endl;
    cout<<"BMS College of Engineering"<<endl<<"P.O. Box No.: 1908"<<endl<<"Bull Temple Road, Basavanagudi"<<endl;
    cout<<"Bangalore-560019"<<endl<<"Karnataka, India."<<endl<<endl;
    cout<<"Location & Area : Located in the heart of Bangalore, the Garden City of India, BMSCE is about 5 KMs from the Central Railway Station."<<endl<<"The campus area is 11 Acres 30 Guntas with a built up area of 99,500 Sq.M.."<<endl<<endl;
    cout<<"Principle's Details:"<<endl;
    contact_module();
    
}



int main(){
    modules m;
    con_det n;
    m.bmsce();
    int b,y ;
    int choice=1;
    do
     {
     	
		cout<<endl<<"Which module would you like to visit?:  ";
        cin >> b;
    switch(b){
        case 1:
        {
            m.courses_module();
            break;
        }
        case 2:
        {
            m.eligibility_module();
            cout << "to contact the faculty please enter 1 and to exit 0" << endl;
            cin >> y; 
            if (y==1)
               m.courses_module();
            break;
        }
        case 3:{
            m.placement_module();
            break;
        }
        case 4:{
            n.contact();
            break;
        }
        default:
        cout<<"enter correct option";
    }
    cout<<endl<<"to continue please enter 1?";
        cin>>choice;
     }while(choice);



    return 0;
}
