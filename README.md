# markup-hw-05

css

.features-item::before {
content: "";
display: block;
border: 1px solid var(--light-slate);
border-radius: 4px;
width: 264px;
height: 112px;

background: var(--cloud);
background-repeat: no-repeat;
background-position: center;
}

.icon-antenna::before {
background-image: url(../images/icons/antenna.svg);
}

.icon-clock::before {
background-image: url(../images/icons/clock.svg);
}

.icon-diagram::before {
background-image: url(../images/icons/diagram.svg);
}

.icon-astronaut::before {
background-image: url(../images/icons/astronaut.svg);
}

.list .features-item + .features-item {
margin-left: 24px;
}
