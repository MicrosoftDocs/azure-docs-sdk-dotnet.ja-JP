<Type Name="KeyValueStoreNotification" FullName="System.Fabric.KeyValueStoreNotification">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreNotification" />
  <TypeSignature Language="F#" Value="type KeyValueStoreNotification = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>セカンダリ レプリカによって受信された、レプリケートされた操作のすべての情報が含まれています。</para>
    </summary>
    <remarks>
      <para>以下を参照してください。<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="IsDelete">
      <MemberSignature Language="C#" Value="public bool IsDelete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.IsDelete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDelete : bool" Usage="System.Fabric.KeyValueStoreNotification.IsDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>これは、レプリケートされた削除操作であることを示します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合、これは、レプリケートされた削除操作です。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreItemMetadata Metadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As KeyValueStoreItemMetadata" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Fabric.KeyValueStoreItemMetadata" Usage="System.Fabric.KeyValueStoreNotification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはレプリケートされたこの操作を記述するメタデータを設定します。</para>
        </summary>
        <value>
          <para>これを記述するメタデータは、操作をレプリケートします。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public byte[] Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Byte()" />
      <MemberSignature Language="F#" Value="member this.Value : byte[]" Usage="System.Fabric.KeyValueStoreNotification.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこの操作のレプリケートされたデータを (該当する場合) に設定します。 これは、削除操作の場合は null です。</para>
        </summary>
        <value>
          <para>このデータ (存在する場合) は、操作をレプリケートします。 これは、削除操作の場合は null です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>