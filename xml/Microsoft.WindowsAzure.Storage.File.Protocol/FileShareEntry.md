<Type Name="FileShareEntry" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry">
  <TypeSignature Language="C#" Value="public sealed class FileShareEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileShareEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileShareEntry" />
  <TypeSignature Language="F#" Value="type FileShareEntry = class" />
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
            <span data-ttu-id="60703-101">共有の操作を一覧表示する XML 応答で返される共有項目を表します。</span><span class="sxs-lookup"><span data-stu-id="60703-101">Represents a share item returned in the XML response for a share listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Metadata" />
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
            <span data-ttu-id="60703-102">共有のユーザー定義メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="60703-102">Gets the user-defined metadata for the share.</span></span>
            </summary>
        <value><span data-ttu-id="60703-103">名前と値のペアのコレクションとしての共有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="60703-103">The share's metadata, as a collection of name-value pairs.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Name" />
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
            <span data-ttu-id="60703-104">共有の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="60703-104">Gets the name of the share.</span></span>
            </summary>
        <value><span data-ttu-id="60703-105">共有の名前です。</span><span class="sxs-lookup"><span data-stu-id="60703-105">The share's name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileShareProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileShareProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileShareProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.File.FileShareProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileShareProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60703-106">共有のシステム プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="60703-106">Gets the share's system properties.</span></span>
            </summary>
        <value><span data-ttu-id="60703-107">共有のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="60703-107">The share's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60703-108">存在する場合は、共有のスナップショットの時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="60703-108">Gets the share's snapshot time, if any.</span></span>
            </summary>
        <value><span data-ttu-id="60703-109">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="60703-109">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the share is a snapshot.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry.Uri" />
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
            <span data-ttu-id="60703-110">共有の URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="60703-110">Gets the share's URI.</span></span>
            </summary>
        <value><span data-ttu-id="60703-111">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="60703-111">The absolute URI to the share.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>