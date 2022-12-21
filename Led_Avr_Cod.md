 * Created: 10/08/2022 08:43:13 Þ.Ù
 * Author: modiri
 */

#include <io.h>
#include <delay.h>
void main(void)
{
  DDRA.0=1; 
  DDRA.1=0;
  PINA.1=1;
  PORTA.0=1;
while (1)
    {    
     if( PINA.1=1;)
     {
       PORTA.0=!PORTA.0 ;
       delay_ms(100);
    }
}

