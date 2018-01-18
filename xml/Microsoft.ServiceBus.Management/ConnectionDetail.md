<Type Name="ConnectionDetail" FullName="Microsoft.ServiceBus.Management.ConnectionDetail">
  <TypeSignature Language="C#" Value="public class ConnectionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.ConnectionDetail" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionDetail" />
  <TypeSignature Language="F#" Value="type ConnectionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ConnectionDetail", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="bf0ac-101">Service bus の接続に関連付けられている詳細を表します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-101">Represents the details associated with the service bus connection.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.ConnectionDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationType">
      <MemberSignature Language="C#" Value="public string AuthorizationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.AuthorizationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationType : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.AuthorizationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="AuthorizationType", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bf0ac-102">取得または接続の承認の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-102">Gets or sets the authorization type for the connection.</span></span></summary>
        <value><span data-ttu-id="bf0ac-103">接続の承認の種類。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-103">The authorization type for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ConnectionString", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bf0ac-104">取得または接続に関連付けられている接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-104">Gets or sets the connection string associated with the connection.</span></span></summary>
        <value><span data-ttu-id="bf0ac-105">接続に関連付けられている接続文字列。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-105">The connection string associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="KeyName", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bf0ac-106">取得または接続に関連付けられているキーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-106">Gets or sets the key name associated with the connection.</span></span></summary>
        <value><span data-ttu-id="bf0ac-107">接続に関連付けられているキーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-107">The key name associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IEnumerable(Of AccessRights)" />
      <MemberSignature Language="F#" Value="member this.Rights : seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Rights", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bf0ac-108">取得または接続に関連付けられているアクセス権を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-108">Gets or sets the access rights associated with the connection.</span></span></summary>
        <value><span data-ttu-id="bf0ac-109">接続に関連付けられているアクセス権。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-109">The access rights associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SecondaryConnectionString", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bf0ac-110">取得または接続に関連付けられているセカンダリ接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-110">Gets or sets the secondary connection string associated with the connection.</span></span></summary>
        <value><span data-ttu-id="bf0ac-111">接続に関連付けられているセカンダリ接続文字列。</span><span class="sxs-lookup"><span data-stu-id="bf0ac-111">The secondary connection string associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>