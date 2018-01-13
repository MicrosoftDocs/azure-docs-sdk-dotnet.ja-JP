<Type Name="ListBlobEntry" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry">
  <TypeSignature Language="C#" Value="public sealed class ListBlobEntry : Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlobEntry extends System.Object implements class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlobEntry&#xA;Implements IListBlobEntry" />
  <TypeSignature Language="F#" Value="type ListBlobEntry = class&#xA;    interface IListBlobEntry" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Blob の操作を一覧表示する XML 応答で返される blob 項目を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyState As CopyState" />
      <MemberSignature Language="F#" Value="member this.CopyState : Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            最新または保留中のコピー操作の状態を取得します。
            </summary>
        <value>A<see cref="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" />コピー状態を格納しているオブジェクトまたは<c>null</c>この blob の blob の状態のコピーが存在しない場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Metadata" />
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
            Blob 項目のユーザー定義メタデータを取得します。
            </summary>
        <value><see cref="T:System.Collections.Generic.IDictionary`2" />名前/値ペアのコレクションとして blob 項目のメタデータを含むオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Name" />
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
            Blob 項目の名前を取得します。
            </summary>
        <value>Blob 項目の名前を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As BlobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob 項目の システムのプロパティを取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.SnapshotTime" />
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
            この blob がスナップショットの場合、blob のスナップショットが作成された日時を取得します。
            </summary>
        <value>Blob がスナップショットである場合は、blob のスナップショットの時間それ以外の場合、 <c>null</c>です。</value>
        <remarks>
            このプロパティの値は、blob がスナップショットでない場合は、 <c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Uri" />
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
            Blob 項目の URI を取得します。
            </summary>
        <value>Blob 項目の絶対 URI です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>