.navbar ul li ::after{
    content: '';
    height: 3px;
    width: 0;
    background: #cbb2cc;
    position: absolute;
    left: 0;
    bottom:-10px;
    transition: 0.5s;
}
.navbar ul li :hover::after{
    width: 100%;
