# Unit 4: Rotational Motion

## Translational and Rotational Motions

- **Translational Motion**: Jab object ek straight line mein move karta hai, usse translational motion kehte hain. Isme object ki position change hoti hai.

- **Rotational Motion**: Jab object apne axis ke around rotate karta hai, usse rotational motion kehte hain. Example: Earth ka apne axis ke around ghoomna.

  - In dono motions mein difference ye hai ki translational motion mein object ki position change hoti hai, lekin rotational motion mein object ka orientation change hota hai.

## Torque and Angular Momentum

- **Torque**: Torque ek force hoti hai jo rotation ko produce karti hai. Jab force ko kisi point se apply kiya jata hai, aur uska distance us point se ek particular axis tak hota hai, toh torque generate hoti hai. 

  - Formula for Torque:
  
\[
  \tau = r \cdot F \cdot \sin \theta
\]
  
  Jahan:
  - \tau is the torque,
  - r is the distance from the axis of rotation,
  - F is the applied force,
  - \theta is the angle between force and radius vector.

- **Angular Momentum**: Angular momentum ek object ke rotational motion ki quantity hoti hai. Ye linear momentum ka rotational counterpart hai.

  - Formula for Angular Momentum:
  
\[
  L = r \cdot p
\]
  
  Jahan:
  - L is angular momentum,
  - r is the position vector,
  - p is linear momentum.

  - Angular momentum ka unit hota hai **kg m²/s**.

- **Conservation of Angular Momentum**: Agar external torque nahi hai, toh angular momentum conserved hoti hai. Matlab, ek isolated system mein angular momentum constant rahta hai.

  - Example: Ice skater ka spin karte waqt speed badhna jab unke arms close hote hain, yeh angular momentum conservation ka example hai.

## Moment of Inertia

- **Moment of Inertia**: Moment of inertia ek object ki property hoti hai jo uski rotational motion ko resist karne ki ability ko define karti hai. Ye linear inertia ka rotational counterpart hai.

  - Formula for Moment of Inertia:
  
\[
  I = \sum m_i r_i^2
\]
  
  Jahan:
  - I is moment of inertia,
  - m_i is the mass of the particle,
  - r_i is the distance from the axis of rotation.

  - Moment of inertia ka unit **kg m²** hota hai.

- **Radius of Gyration**: Ye ek imaginary point hota hai jahan se agar pura mass concentrated hota, toh object ka moment of inertia same hota. Radius of gyration ko k se represent kiya jata hai.

  - Formula:
  
\[
  I = m k^2
\]

## Theorems of Parallel and Perpendicular Axes

- **Parallel Axis Theorem**: Agar kisi object ka moment of inertia axis ke around known hai, toh object ka moment of inertia kisi parallel axis ke around calculate karne ke liye:

\[
  I = I_{\text{cm}} + m d^2
\]
  
  Jahan:
  - I_{\text{cm}} is moment of inertia about center of mass,
  - m is mass of the object,
  - d is the distance between the center of mass and the new axis.

- **Perpendicular Axis Theorem**: Agar object flat hai aur ek plane mein lie karta hai, toh uska moment of inertia kisi plane ke upar perpendicular axes ke around:

\[
  I_z = I_x + I_y
\]
  
  Jahan:
  - I_z is moment of inertia about the perpendicular axis,
  - I_x and I_y are moments of inertia about the x and y axes.

## Moment of Inertia of Common Objects

- **Rod** (about its center):
  
\[
  I_{\text{rod}} = \frac{1}{12} m L^2
\]
  
- **Disc** (about its center):
  
\[
  I_{\text{disc}} = \frac{1}{2} m R^2
\]

- **Ring** (about its center):
  
\[
  I_{\text{ring}} = m R^2
\]

- **Solid Sphere** (about its center):
  
\[
  I_{\text{sphere}} = \frac{2}{5} m R^2
\]

- **Hollow Sphere** (about its center):
  
\[
  I_{\text{hollow sphere}} = \frac{2}{3} m R^2
\]

### Summary

1. **Rotational Motion**: Ek object jab apne axis ke around ghoomta hai toh usko rotational motion kehte hain. Isme torque aur angular momentum important concepts hain.
2. **Moment of Inertia**: Ye ek object ki rotational inertia hoti hai, jo us object ke mass distribution par depend karti hai.
3. **Conservation of Angular Momentum**: Angular momentum constant rehti hai jab external torque nahi hota.

Is unit mein rotational motion ke basics, torque, angular momentum, and moment of inertia ke important concepts ko samjhaya gaya hai. Yeh unit engineering mechanics aur physics ki problems ko solve karne ke liye essential hai.
