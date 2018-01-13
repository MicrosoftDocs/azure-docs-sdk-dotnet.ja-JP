<Type Name="NamespaceAvailability" FullName="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability">
  <TypeSignature Language="C#" Value="public class NamespaceAvailability : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceAvailability extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceAvailability&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type NamespaceAvailability = class&#xA;    interface IExtensibleDataObject" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NamespaceAvailability", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="7f24d-101">指定されたサービス名前空間の可用性を表します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-101">Represents the availability of the given service namespace.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7f24d-102"><see cref="T:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public bool Available { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Available" />
      <MemberSignature Language="VB.NET" Value="Public Property Available As Boolean" />
      <MemberSignature Language="F#" Value="member this.Available : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="Result", Order=101)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7f24d-103">取得または名前空間が使用できるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-103">Gets or sets whether the namespace is available.</span></span></summary>
        <value><span data-ttu-id="7f24d-104">名前空間がある場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="7f24d-104">true if the namespace is available; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.ExtensionData" />
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
        <summary><span data-ttu-id="7f24d-105">取得または名前空間に関連付けられている拡張機能のデータ オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-105">Gets or sets the extension data object associated with the namespace.</span></span></summary>
        <value><span data-ttu-id="7f24d-106">名前空間に関連付けられている拡張機能のデータ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7f24d-106">The extension data object associated with the namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Management.UnavailableReason Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.Management.UnavailableReason Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As UnavailableReason" />
      <MemberSignature Language="F#" Value="member this.Reason : Microsoft.Azure.NotificationHubs.Management.UnavailableReason with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Management.UnavailableReason</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7f24d-107">取得または名前空間が使用できない理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-107">Gets or sets the reason for unavailability of a namespace.</span></span></summary>
        <value><span data-ttu-id="7f24d-108">名前空間の非可用理由です。</span><span class="sxs-lookup"><span data-stu-id="7f24d-108">The reason for unavailability of a namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonDetail">
      <MemberSignature Language="C#" Value="public string ReasonDetail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonDetail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.ReasonDetail" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonDetail As String" />
      <MemberSignature Language="F#" Value="member this.ReasonDetail : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.ReasonDetail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="ReasonDetail", Order=102)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7f24d-109">取得または名前空間に関連付けられている理由に関する詳細な情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f24d-109">Gets or sets the detailed info regarding the reason associated with the namespace.</span></span></summary>
        <value><span data-ttu-id="7f24d-110">名前空間に関連付けられている理由に関する詳細な情報です。</span><span class="sxs-lookup"><span data-stu-id="7f24d-110">The detailed info regarding the reason associated with the namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.Azure.NotificationHubs.Management.NamespaceAvailability.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7f24d-111">データ コントラクト シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="7f24d-111">The data contract serializer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>