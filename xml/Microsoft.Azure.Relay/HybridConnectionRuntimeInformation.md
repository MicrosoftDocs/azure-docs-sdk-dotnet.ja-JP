<Type Name="HybridConnectionRuntimeInformation" FullName="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation">
  <TypeSignature Language="C#" Value="public class HybridConnectionRuntimeInformation : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionRuntimeInformation extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionRuntimeInformation&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type HybridConnectionRuntimeInformation = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="HybridConnectionDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="35a59-101">HybridConnection に関するランタイム情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="35a59-101">Provides runtime information about a HybridConnection.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="35a59-102">HybridConnection が作成された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a59-102">Gets the time the HybridConnection was created.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerCount">
      <MemberSignature Language="C#" Value="public int ListenerCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.ListenerCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenerCount : int" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.ListenerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="35a59-103">この HybridConnection のリスナーの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a59-103">Gets the number of listeners for this HybridConnection.</span></span></summary>
        <value><span data-ttu-id="35a59-104">この HybridConnection のリスナーの数。</span><span class="sxs-lookup"><span data-stu-id="35a59-104">The number of listeners for this HybridConnection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresClientAuthorization">
      <MemberSignature Language="C#" Value="public bool RequiresClientAuthorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresClientAuthorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.RequiresClientAuthorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequiresClientAuthorization As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresClientAuthorization : bool" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.RequiresClientAuthorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="35a59-105">この HybridConnection のクライアントの承認が必要かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a59-105">Gets a value indicating whether client authorization is needed for this HybridConnection.</span></span></summary>
        <value><span data-ttu-id="35a59-106">この HybridConnection; クライアントの承認が必要な場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="35a59-106">true if client authorization is needed for this HybridConnection; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Runtime.Serialization.IExtensibleDataObject.ExtensionData">
      <MemberSignature Language="C#" Value="System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.System#Runtime#Serialization#IExtensibleDataObject#ExtensionData" />
      <MemberSignature Language="VB.NET" Value=" Property ExtensionData As ExtensionDataObject Implements IExtensibleDataObject.ExtensionData" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.System.Runtime.Serialization.IExtensibleDataObject.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="35a59-107">HybridConnection が更新された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="35a59-107">Gets the time when the HybridConnection was updated.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string" Usage="Microsoft.Azure.Relay.HybridConnectionRuntimeInformation.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="35a59-108">このインスタンスに関連付けられているユーザーのメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="35a59-108">Gets the user metadata associated with this instance.</span></span></summary>
        <value><span data-ttu-id="35a59-109">このインスタンスに関連付けられているユーザーのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="35a59-109">The user metadata associated with this instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>