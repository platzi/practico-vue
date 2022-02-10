<template>
    <div>
        <svg
            viewBox="0 0 300 200"
        >
            <line
                stroke="#c4c4c4"
                stroke-width="2"
                x1="0"
                y1="100"
                x2="300"
                y2="100"
            />
            <polyline
                fill="none"
                stroke="#0689B0"
                stroke-width="2"
                points="0,0 100,100 200,100 300,200"
            />
            <line
                stroke="#04b500"
                stroke-width="2"
                x1="200"
                y1="0"
                x2="200"
                y2="200"
            />
        </svg>
        <p>Últimos 30 días</p>
    </div>
</template>


<style scoped>
svg {
  width: 100%;
}
p {
  text-align: center;
}
</style>