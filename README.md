# Hackathon RC 2017

Ce programme a été développé dans le cadre de l'édition 2017 du Hackathon de Radio-Canada par une équipe de 5 personnes.

Il s'agit d'un prototype démontrant la faisabilité d'une nouvelle fonctionnalité à ajouter à la version Android de l'application Radio-Canada Première.

La fonctionnalité en question insère entre deux segments d'une liste de lecture une narration du titre du segment à venir.

Le prototype utilise Neuro (une API fournie par Radio-Canada) pour récupérer les listes de lectures suggérées dans l'application Radio-Canada Première. Les titres des segments audio sont ensuite envoyés à l'outil "text-to-speech" de Microsoft Azure, lequel nous retourne un fichier MP3 contenant la narration du titre envoyé. Le fichier MP3 reçu est ensuite joué en préambule au segment audio auquel il réfère. L'usager est ainsi informé du titre du segment audio qu'il s'apprête à écouter sans avoir à consulter son appareil mobile.

Comme il ne s'agit que d'un prototype, l'application fonctionnera pendant 30 jours après sa publication (i.e. jusqu'au 23 avril 2017). Après ce délais, la licence Microsoft Azure utilisée pour le développement expirera et le prototype ne pourra plus fonctionner. De notre prototype, il ne restera après cette date que le code source.
