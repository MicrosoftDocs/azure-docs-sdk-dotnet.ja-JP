<Type Name="AzureSearchIndexWriteBehavior" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior">
  <TypeSignature Language="C#" Value="public static class AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AzureSearchIndexWriteBehavior extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="F#" Value="type AzureSearchIndexWriteBehavior = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f5cd-101">アップサート文書の Azure Search インデックスには、動作を記述します。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-101">Write behavior when upserting documents into an Azure Search Index.</span></span>
            <span data-ttu-id="8f5cd-102">プロパティ<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexSink" />です。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-102">A property of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexSink" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public const string Merge;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Merge" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Merge" />
      <MemberSignature Language="VB.NET" Value="Public Const Merge As String " />
      <MemberSignature Language="F#" Value="val mutable Merge : string" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Merge" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f5cd-103">マージでは、指定されたフィールドで、既存のドキュメントを更新します。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-103">Merge updates an existing document with the specified fields.</span></span> <span data-ttu-id="8f5cd-104">マージで指定された任意のフィールドは、ドキュメント内の既存のフィールドで置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-104">Any field specified in a merge will replace the existing field in the document.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public const string Upload;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Upload" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Upload" />
      <MemberSignature Language="VB.NET" Value="Public Const Upload As String " />
      <MemberSignature Language="F#" Value="val mutable Upload : string" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Upload" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f5cd-105">ドキュメントは、それが新しい場合は、挿入、更新または置換が存在する場合は。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-105">The document will be inserted if it is new and updated/replaced if it exists.</span></span> <span data-ttu-id="8f5cd-106">更新プログラムを実行する場合は、すべてのフィールドが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8f5cd-106">If an update is performed, all fields will be replaced.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>