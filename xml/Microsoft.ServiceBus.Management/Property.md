<Type Name="Property" FullName="Microsoft.ServiceBus.Management.Property">
  <TypeSignature Language="C#" Value="public class Property : ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Property extends System.Object implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.Property" />
  <TypeSignature Language="VB.NET" Value="Public Class Property&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type Property = class&#xA;    interface ICloneable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="Property", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="2c079-101">サービス バスのプロパティを表します。</span><span class="sxs-lookup"><span data-stu-id="2c079-101">Represents the service bus property.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Property ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.Property.#ctor" />
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
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.Property.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="property.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ICloneable.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2c079-102">このインスタンスのコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="2c079-102">Creates a copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="2c079-103">作成されたこのインスタンスのコピー。</span><span class="sxs-lookup"><span data-stu-id="2c079-103">A created copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public DateTime Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Property.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As DateTime" />
      <MemberSignature Language="F#" Value="member this.Created : DateTime" Usage="Microsoft.ServiceBus.Management.Property.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Created", Order=102)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-104">取得またはプロパティの作成時に設定します。</span><span class="sxs-lookup"><span data-stu-id="2c079-104">Gets or sets when the property was created.</span></span></summary>
        <value><span data-ttu-id="2c079-105">プロパティが作成された日付。</span><span class="sxs-lookup"><span data-stu-id="2c079-105">The date when the property was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Modified">
      <MemberSignature Language="C#" Value="public DateTime Modified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Modified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Property.Modified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Modified As DateTime" />
      <MemberSignature Language="F#" Value="member this.Modified : DateTime" Usage="Microsoft.ServiceBus.Management.Property.Modified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Modified", Order=103)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-106">取得またはプロパティが変更された日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="2c079-106">Gets or sets when the property was modified.</span></span></summary>
        <value><span data-ttu-id="2c079-107">プロパティが変更された日付。</span><span class="sxs-lookup"><span data-stu-id="2c079-107">The date when the property was modified.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Property.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Management.Property.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Name", Order=100)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-108">プロパティの名前を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="2c079-108">Gets or sets the name of the property.</span></span></summary>
        <value><span data-ttu-id="2c079-109">プロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="2c079-109">The name of the property.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revision">
      <MemberSignature Language="C#" Value="public long Revision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Revision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Property.Revision" />
      <MemberSignature Language="VB.NET" Value="Public Property Revision As Long" />
      <MemberSignature Language="F#" Value="member this.Revision : int64 with get, set" Usage="Microsoft.ServiceBus.Management.Property.Revision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Revision", Order=104)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-110">取得またはプロパティのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="2c079-110">Gets or sets the version of the property.</span></span></summary>
        <value><span data-ttu-id="2c079-111">プロパティのバージョンです。</span><span class="sxs-lookup"><span data-stu-id="2c079-111">The version of the property.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.Property.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Management.Property.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-112">プロパティに関連付けられているシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="2c079-112">The serializer associated with the property.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Property.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.ServiceBus.Management.Property.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="Value", Order=101)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c079-113">プロパティ値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="2c079-113">Gets or sets the property value.</span></span></summary>
        <value><span data-ttu-id="2c079-114">プロパティ値。</span><span class="sxs-lookup"><span data-stu-id="2c079-114">The property value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>