<Type Name="TrafficManagerNameAvailabilityInner" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner">
  <TypeSignature Language="C#" Value="public class TrafficManagerNameAvailabilityInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TrafficManagerNameAvailabilityInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TrafficManagerNameAvailabilityInner" />
  <TypeSignature Language="F#" Value="type TrafficManagerNameAvailabilityInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c53e5-101">トラフィック マネージャーの名前の可用性の応答を表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="c53e5-101">Class representing a Traffic Manager Name Availability response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerNameAvailabilityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-102">TrafficManagerNameAvailabilityInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-102">Initializes a new instance of the TrafficManagerNameAvailabilityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerNameAvailabilityInner (string name = null, string type = null, Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional type As String = null, Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner : string * string * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner" Usage="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner (name, type, nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c53e5-103">相対名。</span><span class="sxs-lookup"><span data-stu-id="c53e5-103">The relative name.</span></span></param>
        <param name="type"><span data-ttu-id="c53e5-104">Traffic Manager プロファイル リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c53e5-104">Traffic Manager profile resource type.</span></span></param>
        <param name="nameAvailable"><span data-ttu-id="c53e5-105">相対名が使用しているかいないかどうかについて説明します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-105">Describes whether the relative name is available or not.</span></span></param>
        <param name="reason"><span data-ttu-id="c53e5-106">名前が当てはまる場合に使用可能な理由です。</span><span class="sxs-lookup"><span data-stu-id="c53e5-106">The reason why the name is not available, when applicable.</span></span></param>
        <param name="message"><span data-ttu-id="c53e5-107">名前が当てはまる場合に使用可能な理由を説明する説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c53e5-107">Descriptive message that explains why the name is not available, when applicable.</span></span></param>
        <summary>
            <span data-ttu-id="c53e5-108">TrafficManagerNameAvailabilityInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-108">Initializes a new instance of the TrafficManagerNameAvailabilityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-109">取得または名前が当てはまる場合に使用可能な理由を説明するわかりやすいメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-109">Gets or sets descriptive message that explains why the name is not available, when applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-110">取得または相対名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-110">Gets or sets the relative name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-111">取得または設定は、相対名が使用しているかいないかどうかについて説明します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-111">Gets or sets describes whether the relative name is available or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-112">取得または名前が当てはまる場合に使用可能な理由を設定します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-112">Gets or sets the reason why the name is not available, when applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c53e5-113">取得または traffic Manager プロファイル リソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="c53e5-113">Gets or sets traffic Manager profile resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>