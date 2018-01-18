<Type Name="Usage" FullName="Microsoft.Azure.Management.Network.Models.Usage">
  <TypeSignature Language="C#" Value="public class Usage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Usage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.Usage" />
  <TypeSignature Language="VB.NET" Value="Public Class Usage" />
  <TypeSignature Language="F#" Value="type Usage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ad6be-101">ネットワーク リソースの使用方法を説明します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-101">Describes network resource usage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Usage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-102">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-102">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage (long currentValue, long limit, Microsoft.Azure.Management.Network.Models.UsageName name, string id = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 currentValue, int64 limit, class Microsoft.Azure.Management.Network.Models.UsageName name, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Usage.#ctor(System.Int64,System.Int64,Microsoft.Azure.Management.Network.Models.UsageName,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (currentValue As Long, limit As Long, name As UsageName, Optional id As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.Usage : int64 * int64 * Microsoft.Azure.Management.Network.Models.UsageName * string -&gt; Microsoft.Azure.Management.Network.Models.Usage" Usage="new Microsoft.Azure.Management.Network.Models.Usage (currentValue, limit, name, id)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="currentValue" Type="System.Int64" />
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Network.Models.UsageName" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="currentValue"><span data-ttu-id="ad6be-103">使用率の現在の値。</span><span class="sxs-lookup"><span data-stu-id="ad6be-103">The current value of the usage.</span></span></param>
        <param name="limit"><span data-ttu-id="ad6be-104">使用状況の制限。</span><span class="sxs-lookup"><span data-stu-id="ad6be-104">The limit of usage.</span></span></param>
        <param name="name"><span data-ttu-id="ad6be-105">使用法の種類の名前。</span><span class="sxs-lookup"><span data-stu-id="ad6be-105">The name of the type of usage.</span></span></param>
        <param name="id"><span data-ttu-id="ad6be-106">リソース識別子。</span><span class="sxs-lookup"><span data-stu-id="ad6be-106">Resource identifier.</span></span></param>
        <summary>
            <span data-ttu-id="ad6be-107">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-107">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public long CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Usage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int64 with get, set" Usage="Microsoft.Azure.Management.Network.Models.Usage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-108">取得または使用率の現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-108">Gets or sets the current value of the usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Usage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.Usage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-109">リソース識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-109">Gets resource identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Usage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64 with get, set" Usage="Microsoft.Azure.Management.Network.Models.Usage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-110">取得または使用率の制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-110">Gets or sets the limit of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.UsageName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Usage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Network.Models.UsageName with get, set" Usage="Microsoft.Azure.Management.Network.Models.Usage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-111">取得または使用法の種類の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-111">Gets or sets the name of the type of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public static string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Usage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Network.Models.Usage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-112">測定単位を説明する列挙です。</span><span class="sxs-lookup"><span data-stu-id="ad6be-112">An enum describing the unit of measurement.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Usage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ad6be-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ad6be-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ad6be-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ad6be-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>