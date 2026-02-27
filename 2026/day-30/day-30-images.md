TASK 1:

<img width="649" height="312" alt="Screenshot from 2026-02-27 18-30-55" src="https://github.com/user-attachments/assets/fec6c015-f11d-450c-b511-a750eebd5563" />

<img width="1037" height="993" alt="Screenshot from 2026-02-27 18-32-31" src="https://github.com/user-attachments/assets/da0bc05c-a1df-441b-8b08-951951d216b4" />

Alpine has lesser number of dependencies, libraries and tools. Therefore, the image of alpine is nearly 10x smaller than that of ubuntu.

<img width="755" height="447" alt="Screenshot from 2026-02-27 18-49-50" src="https://github.com/user-attachments/assets/dae9850a-12b8-4cc9-8a2b-24dfb0da5021" />


TASK 2:

<img width="879" height="394" alt="Screenshot from 2026-02-27 18-51-15" src="https://github.com/user-attachments/assets/3b6c1537-dfb9-437a-a974-44ce554e951b" />

Every image in docker is made up of multiple layers. Each layer is responsible for a certain instruction, these instructions together as a whole forms the overall instructions which will be run in an image. Now if a certain layer has instructions which can bring some changes in the filesystem, like FROM, RUN, COPY etc, those layers will show some size. WHile the other layers which only modifies metadata, like EXPOSE, WORKDIR, ENTRYPOINT it will show 0B.


TASK 4:

<img width="1742" height="851" alt="Screenshot from 2026-02-27 20-58-39" src="https://github.com/user-attachments/assets/8ab362bf-1a8a-4158-841a-d80f549e58f2" />


TASK 5:

<img width="723" height="919" alt="Screenshot from 2026-02-27 21-03-31" src="https://github.com/user-attachments/assets/c75522d2-dae9-4cd0-9139-52e0ee867b94" />
