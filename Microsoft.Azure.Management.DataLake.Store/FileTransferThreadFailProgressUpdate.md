<Type Name="FileTransferThreadFailProgressUpdate" FullName="Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate">
  <TypeSignature Language="C#" Value="public delegate void FileTransferThreadFailProgressUpdate(TransferMetadata failedFile);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FileTransferThreadFailProgressUpdate extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub FileTransferThreadFailProgressUpdate(failedFile As TransferMetadata)" />
  <TypeSignature Language="F#" Value="type FileTransferThreadFailProgressUpdate = delegate of TransferMetadata -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="failedFile" Type="Microsoft.Azure.Management.DataLake.Store.TransferMetadata" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="failedFile">To be added.</param>
    <summary>
            <span data-ttu-id="41eed-101">ファイルが予期せず終了スレッド転送が発生したときに呼び出されるデリゲートを表します。</span><span class="sxs-lookup"><span data-stu-id="41eed-101">Represents a delegate that is called in the event of a thread transfering a file terminating unexpectedly.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>