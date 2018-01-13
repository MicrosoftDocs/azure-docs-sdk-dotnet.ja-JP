<Type Name="KeyRotationEntity" FullName="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity">
  <TypeSignature Language="C#" Value="public class KeyRotationEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyRotationEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyRotationEntity" />
  <TypeSignature Language="F#" Value="type KeyRotationEntity = class" />
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
            キーの交換に使用されるエンティティ
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.ETag" />
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
            取得またはエンティティの現在の ETag を設定します。
            </summary>
        <value>エンティティの ETag を表す文字列。</value>
        <remarks>この値を設定 ' *' を更新操作の一部としてエンティティを無条件で上書きします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.EntityProperty this[string key] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Table.EntityProperty" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">プロパティの名前を含む文字列。</param>
        <summary>
            取得またはプロパティの名前を指定されたエンティティのプロパティを設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.PartitionKey" />
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
            取得またはエンティティのパーティション キーを設定します。
            </summary>
        <value>エンティティのパーティション キー値を表す文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IReadOnlyDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティ名でインデックス付けされた、テーブル エンティティのプロパティを取得します。
            </summary>
        <value><see cref="T:System.Collections.Generic.IDictionary`2" />エンティティのプロパティを含むオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.RowKey" />
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
            取得またはエンティティの行キーを設定します。
            </summary>
        <value>エンティティの行のキー値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset" Usage="Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティのタイムスタンプを設定します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>