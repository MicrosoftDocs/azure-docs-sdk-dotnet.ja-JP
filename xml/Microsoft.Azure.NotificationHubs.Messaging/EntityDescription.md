<Type Name="EntityDescription" FullName="Microsoft.Azure.NotificationHubs.Messaging.EntityDescription">
  <TypeSignature Language="C#" Value="public abstract class EntityDescription : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityDescription extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityDescription&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type EntityDescription = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.NotificationHubDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="cfa78-101">エンティティの説明を表します。</span><span class="sxs-lookup"><span data-stu-id="cfa78-101">Represents the description of an entity.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.EntityDescription.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityDescription.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cfa78-102">追加データを格納する構造体を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cfa78-102">Gets or sets the structure that contains extra data.</span></span></summary>
        <value><span data-ttu-id="cfa78-103">このデータ コントラクトに属していると認識されないデータを格納する <see cref="T:System.Runtime.Serialization.ExtensionDataObject" />。</span><span class="sxs-lookup"><span data-stu-id="cfa78-103">An <see cref="T:System.Runtime.Serialization.ExtensionDataObject" /> that contains data that is not recognized as belonging to the data contract.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.EntityDescription.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.Azure.NotificationHubs.Messaging.EntityDescription.IsReadOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cfa78-104">取得またはエンティティの説明は読み取り専用であるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="cfa78-104">Gets or sets a value that indicates whether the entity description is read-only.</span></span></summary>
        <value><span data-ttu-id="cfa78-105">エンティティの説明が読み取り専用である場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cfa78-105">true if the entity description is read-only; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfReadOnly">
      <MemberSignature Language="C#" Value="protected void ThrowIfReadOnly ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfReadOnly() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.EntityDescription.ThrowIfReadOnly" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfReadOnly ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfReadOnly : unit -&gt; unit" Usage="entityDescription.ThrowIfReadOnly " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cfa78-106">エンティティの説明が読み取り専用の場合は、例外をスローします。</span><span class="sxs-lookup"><span data-stu-id="cfa78-106">Throws an exception if the entity description is read-only.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>