program second
implicit none
real a1,a2,a3,b1,b2,b3,c1,c2,c3,x1,x2,y1,y2
write(*,*) 'Write a1,a2,a3,b1,b2,b3,c1,c2,c3'
read(*,*) a1,a2,a3,b1,b2,b3,c1,c2,c3

x1=((-c1)*b2-b1*(-c2))/(a1*b2-b1*a2)    
y1=(a1*(-c2)-(-c1)*a2)/(a1*b2-b1*a2)

x2=((-c2)*b3-b2*(-c3))/(a2*b3-b2*a3)    
y2=(a2*(-c3)-(-c2)*a3)/(a2*b3-b2*a3) 

if (x1==x2 .and. y1==y2 .and. ((a1*b2-b1*a2/=0) .OR. (a2*b3-b2*a3/=0))) then 
  write(*,*) 'Peresecautsya'
  
  else 
  write(*,*) 'Ne peresecautsya'
  endif
  pause
  end program second
