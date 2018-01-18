<Type Name="ListFileEntry" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry">
  <TypeSignature Language="C#" Value="public sealed class ListFileEntry : Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListFileEntry extends System.Object implements class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListFileEntry&#xA;Implements IListFileEntry" />
  <TypeSignature Language="F#" Value="type ListFileEntry = class&#xA;    interface IListFileEntry" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e55fe-101">XML 応答ファイルの一覧作成操作で返されるファイルの項目を表します。</span><span class="sxs-lookup"><span data-stu-id="e55fe-101">Represents a file item returned in the XML response for a file listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e55fe-102">ファイル項目のユーザー定義メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="e55fe-102">Gets the user-defined metadata for the file item.</span></span>
            </summary>
        <value><span data-ttu-id="e55fe-103">名前と値のペアのコレクションとしてのファイル項目のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="e55fe-103">The file item's metadata, as a collection of name-value pairs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Name" />
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
            <span data-ttu-id="e55fe-104">ファイル項目の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e55fe-104">Gets the name of the file item.</span></span>
            </summary>
        <value><span data-ttu-id="e55fe-105">ファイル項目の名前。</span><span class="sxs-lookup"><span data-stu-id="e55fe-105">The name of the file item.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.File.FileProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e55fe-106">ファイル アイテムのシステム プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="e55fe-106">Gets the file item's system properties.</span></span>
            </summary>
        <value><span data-ttu-id="e55fe-107">ファイル項目のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="e55fe-107">The file item's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFileEntry.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e55fe-108">ファイル項目の URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="e55fe-108">Gets the file item's URI.</span></span>
            </summary>
        <value><span data-ttu-id="e55fe-109">ファイル アイテムの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="e55fe-109">The absolute URI to the file item.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>