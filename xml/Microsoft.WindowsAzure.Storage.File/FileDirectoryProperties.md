<Type Name="FileDirectoryProperties" FullName="Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties">
  <TypeSignature Language="C#" Value="public sealed class FileDirectoryProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileDirectoryProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileDirectoryProperties" />
  <TypeSignature Language="F#" Value="type FileDirectoryProperties = class" />
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
            <span data-ttu-id="87927-101">ディレクトリのシステム プロパティを表します。</span><span class="sxs-lookup"><span data-stu-id="87927-101">Represents the system properties for a directory.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDirectoryProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87927-102">ディレクトリの ETag 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="87927-102">Gets the ETag value for the directory.</span></span>
            </summary>
        <value><span data-ttu-id="87927-103">ディレクトリには、ETag 値が引用符で囲みます。</span><span class="sxs-lookup"><span data-stu-id="87927-103">The directory's quoted ETag value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.IsServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.IsServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87927-104">ディレクトリのサーバー側暗号化の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="87927-104">Gets the directory's server-side encryption state.</span></span>
            </summary>
        <value><span data-ttu-id="87927-105">ディレクトリのサーバー側の暗号化の状態を表すブール値。</span><span class="sxs-lookup"><span data-stu-id="87927-105">A bool representing the directory's server-side encryption state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87927-106">ディレクトリの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="87927-106">Gets the directory's last-modified time.</span></span>
            </summary>
        <value><span data-ttu-id="87927-107">ディレクトリの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="87927-107">The directory's last-modified time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>