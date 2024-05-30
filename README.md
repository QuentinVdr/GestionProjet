# Gestion de projet

## Parcours utilisateur

```mermaid
graph
%% Persona 1 : L'Auditeur Gratuit de Musique Indépendante (Léa)
subgraph Persona1["L'Auditeur Gratuit de Musique Indépendante (Léa)"]

  P1H[Arrive sur la homepage] --> P1R[Recherche de musique]
  P1R --> P1E[Écoute sa musique]
  P1E --> P1I[S'inscrit sur SoundCloud]
  P1E --> P1C[Se connect à son compte]
  P1I --> P1Cr[Créer ses playlists]
  P1C --> P1Cr[Créer ses playlists]
  P1I --> P1A[Ajoute des musiques à ses playlists]
  P1C --> P1A[Ajoute des musiques à ses playlists]
  P1E --> P1D[Découvre de nouveau artiste]
  P1D--> P1P[Partage et commente]

end
```

```mermaid
graph
%% Persona 2 : Le Petit Rappeur qui Publie sa Musique (Kevin)
subgraph Persona2["Le Petit Rappeur qui Publie sa Musique (Kevin)"]

  P2H[Arrive sur la homepage] --> P2I[S'inscrit sur SoundCloud]
  P2H --> P2C[Se connect à son compte]
  P2I --> P2P[Publier sa musique]
  P2C --> P2P
  P2P -->  P2In[Interagir avec sa communauté]
  P2In --> P2S[S'abonne à SoundCloud pour plus de fonctionnalités]

end
```

```mermaid
graph
%% Persona 3 : Étudiant qui Stockent des Fichiers Audio (Marie)
subgraph Persona3["Étudiant qui Stockent des Fichiers Audio (Marie)"]

  P3H[Arrive sur la homepage] --> P3I[S'inscrit sur SoundCloud]
  P3H --> P3C[Se connect à son compte]
  P3I --> P3P[Publier ses fichiers audio]
  P3C --> P3P
  P3P --> P3O[Organiser ses fichiers audio]

end
```
