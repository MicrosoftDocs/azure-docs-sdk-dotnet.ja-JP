<Type Name="CloudTaskExtensions" FullName="Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions">
  <TypeSignature Language="C#" Value="public static class CloudTaskExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudTaskExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudTaskExtensions" />
  <TypeSignature Language="F#" Value="type CloudTaskExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            出力を操作するためのメソッドを提供する<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OutputStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage OutputStorage (this Microsoft.Azure.Batch.CloudTask task, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage OutputStorage(class Microsoft.Azure.Batch.CloudTask task, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions.OutputStorage(Microsoft.Azure.Batch.CloudTask,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorage (task As CloudTask, storageAccount As CloudStorageAccount) As TaskOutputStorage" />
      <MemberSignature Language="F#" Value="static member OutputStorage : Microsoft.Azure.Batch.CloudTask * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudTaskExtensions.OutputStorage (task, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="task" Type="Microsoft.Azure.Batch.CloudTask" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="task">記憶域の出力を取得する対象のタスク。</param>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" />の指定された<see cref="T:Microsoft.Azure.Batch.CloudTask" />です。
            </summary>
        <returns>指定されたタスクの TaskOutputStorage します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>