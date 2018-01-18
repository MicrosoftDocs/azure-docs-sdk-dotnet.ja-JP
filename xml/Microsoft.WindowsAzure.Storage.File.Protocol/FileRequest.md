<Type Name="FileRequest" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileRequest">
  <TypeSignature Language="C#" Value="public static class FileRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileRequest" />
  <TypeSignature Language="F#" Value="type FileRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4454-101">ファイル サービスに対する要求を構築するためのヘルパー メソッドのセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="d4454-101">Provides a set of helper methods for constructing a request against the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WriteSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void WriteSharedAccessIdentifiers (Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies sharedAccessPolicies, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteSharedAccessIdentifiers(class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies sharedAccessPolicies, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileRequest.WriteSharedAccessIdentifiers(Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteSharedAccessIdentifiers (sharedAccessPolicies As SharedAccessFilePolicies, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteSharedAccessIdentifiers : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileRequest.WriteSharedAccessIdentifiers (sharedAccessPolicies, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessPolicies" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sharedAccessPolicies"><span data-ttu-id="d4454-102">共有アクセス ポリシーのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d4454-102">A collection of shared access policies.</span></span></param>
        <param name="outputStream"><span data-ttu-id="d4454-103">出力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="d4454-103">An output stream.</span></span></param>
        <summary>
            <span data-ttu-id="d4454-104">共有アクセス ポリシーのコレクションを XML 形式で指定したストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="d4454-104">Writes a collection of shared access policies to the specified stream in XML format.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>