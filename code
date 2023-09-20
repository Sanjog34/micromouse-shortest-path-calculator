#include<iostream>
#include<stdio.h>
#include<string.h>
#include<stdlib.h>
void sortpath(char path[]);
char emp_path[50];
int b=0; 
 char final_Path[50]={};
int main(){
  printf("enter with no spaces :\nstraight:-S\nleft:-L\nright:-R\nu_turn:-U\nafter entering the path, enter B and press enter\n ");
char path[50]={};
	
    char z='A';
  
for (int i=0;i<=30;i++){
	scanf(" %c",&z);
		if(z=='B'){
		break;
	}
	path[i]=z;}
sortpath(path);
	printf("SHORTEST PATH %s\n",final_Path);
	
}



void sortpath(char path[])
{  int d=0,e,E,A=0,a=0,count,count1=0,Count,Count1=0;
		char path1[50]={};
			e=strlen(path);	
		char temp[3];	
	for(int j=0;j<e;j++){
		if(path[j+1]=='U'){
				temp[0]=path[j];
			temp[1]=path[j+1];
			temp[2]=path[j+2];	
			if(temp[0]=='L' && temp[1]=='U' &&temp[2]=='L'){
					
				path1[a]='S';
			}
			else if(temp[0]=='L' && temp[1]=='U' &&temp[2]=='S'){
					
					path1[a]='R';
			}
			else if(temp[0]=='S' && temp[1]=='U' &&temp[2]=='L'){
						
					path1[a]='R';
			}
			else if(temp[0]=='L' && temp[1]=='U' &&temp[2]=='R'){
					
					path1[a]='U';
						}
						
			else if(temp[0]=='S' && temp[1]=='U' &&temp[2]=='S'){
					
					path1[a]='U';
						}
						
			else if(temp[0]=='R' && temp[1]=='U' &&temp[2]=='L'){
					
					path1[a]='U';
						}
		
			j=j+2;
		
		}
		else{
			path1[a]=path[j];
		}
		a++;	
}
 count=strlen(path1);
 	for(int j=0;j<count;j++){
 			if(path1[j]=='U'){
 				count1++;
 			}
 		
}
if(count1>0){
	char path[50]={};
           E=strlen(path1);
		char Temp[3];		
	for(int J=0;J<E;J++){
		if(path1[J+1]=='U'){
				Temp[0]=path1[J];
			Temp[1]=path1[J+1];
			Temp[2]=path1[J+2];	
			if(Temp[0]=='L' && Temp[1]=='U' &&Temp[2]=='L'){
					
				path[A]='S';
			}
			else if(Temp[0]=='L' && Temp[1]=='U' &&Temp[2]=='S'){
					
					path[A]='R';
			}
			else if(Temp[0]=='S' && Temp[1]=='U' &&Temp[2]=='L'){
						
					path[A]='R';
			}
			else if(Temp[0]=='L' && Temp[1]=='U' &&Temp[2]=='R'){
					
					path[A]='U';
}
			else if(Temp[0]=='S' && Temp[1]=='U' &&Temp[2]=='S'){
					
					path[A]='U';
					}
			else if(Temp[0]=='R' && Temp[1]=='U' &&Temp[2]=='L'){
					
					path[A]='U';
}
			J=J+2;
		}
		else{
			path[A]=path1[J];
		}
		A++;	
}
 Count=strlen(path);
 	for(int j=0;j<Count;j++){
 			if(path[j]=='U'){
 				Count1++;
 			}		
}
if(Count1>0){
sortpath(path);
}
else {
		strcpy(final_Path,path);
   }
}
else{
	strcpy(final_Path,path1);
}
}


