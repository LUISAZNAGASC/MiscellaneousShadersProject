1. DEFINICIÓN DEL RAYO:

WP.xyz=RO.xyz+RD.xyz*DT;

WP.x=RO.x+RD.x*DT;
WP.y=RO.y+RD.y*DT;
WP.z=RO.z+RD.z*DT;

2. DEFINICIÓN DE LA ESFERA:

(WP.x-SP.x)^2.0+(WP.y-SP.y)^2.0+(WP.z-SP.z)^2.0=(SR)^2.0;

3. SUSTITUCIÓN DE LA ESFERA:

WP.x=RO.x+RD.x*DT;
WP.y=RO.y+RD.y*DT;
WP.z=RO.z+RD.z*DT;

(RO.x+RD.x*DT-SP.x)^2.0+(RO.y+RD.y*DT-SP.y)^2.0+(RO.z+RD.z*DT-SP.z)^2.0=(SR)^2.0;

4. DEFINICIÓN DEL VECTOR RELATIVO:

RP.xyz=RO.xyz-SP.xyz;
RP.x=RO.x-SP.x;
RP.y=RO.y-SP.y;
RP.z=RO.z-SP.z;

(RP.x+RD.x*DT)^2.0+(RP.y+RD.y*DT)^2.0+(RP.z+RD.z*DT)^2.0=(SR)^2.0;

5. EXPANSIÓN DE LA FORMA CUADRÁTICA:

(RP.x)^2.0+(RD.x*DT)^2.0+2.0*RP.x*RD.x*DT+(RP.y)^2.0+(RD.y*DT)^2.0+2.0*RP.y*RD.y*DT+(RP.z)^2.0+(RD.z*DT)^2.0+2.0*RP.z*RD.z*DT=(SR)^2.0;

((RD.x)^2.0+(RD.y)^2.0+(RD.z)^2.0)*(DT)^2.0+2.0*(RP.x*RD.x+RP.y*RD.y+RP.z*RD.z)*DT+(RP.x)^2.0+(RP.y)^2.0+(RP.z)^2.0-(SR)^2.0=0.0;

(RD.xyz·RD.xyz)*(DT)^2.0+2.0*(RP.xyz·RD.xyz)*DT+(RP.xyz·RP.xyz)-(SR)^2.0=0.0;

6. DEFINICIÓN DE LOS COEFICIENTES:

QC=(RD.xyz·RD.xyz);

LC=(RP.xyz·RD.xyz);

CC=(RP.xyz·RP.xyz)-(SR)^2.0;

7. DEFINICIÓN DE LA EQUACIÓN CUADRÁTICA:

QC*(DT)^2.0+2.0*LC*DT+CC=0.0;

(QC*(DT)^2.0+2.0*LC*DT+CC)/QC=0.0;

(DT)^2.0+(2.0*LC/QC)*DT+CC/QC=0.0;

8. FINALIZACIÓN CUADRADO PERFECTO:

(DT+KN)^2.0=(DT)^2.0+2.0*KN*DT+(KN)^2.0;

2.0*KN*DT=(2.0*LC/QC)*DT;

KN=LC/QC;

(DT)^2.0+2.0*KN*DT+CC/QC=0.0;

(DT)^2.0+2.0*KN*DT=-CC/QC;

(DT+KN)^2.0=-CC/QC+(KN)^2.0;

9. SOLUCIÓN FINAL:

DT+KN=+(-CC/QC+(KN)^2.0)^0.5;

DT+KN=-(-CC/QC+(KN)^2.0)^0.5;

DT=-KN+(-CC/QC+(KN)^2.0)^0.5;

DT=-KN-(-CC/QC+(KN)^2.0)^0.5;

DT=-LC/QC+((LC/QC)^2.0-CC/QC)^0.5;

DT=-LC/QC-((LC/QC)^2.0-CC/QC)^0.5;