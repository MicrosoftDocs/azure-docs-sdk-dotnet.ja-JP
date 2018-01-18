<Type Name="Usage" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.Usage">
  <TypeSignature Language="C#" Value="public class Usage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Usage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.Usage" />
  <TypeSignature Language="VB.NET" Value="Public Class Usage" />
  <TypeSignature Language="F#" Value="type Usage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a4bfe-101">コンピューティング リソースの使用方法を説明します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-101">Describes Compute Resource Usage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a4bfe-102">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-102">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Usage (int currentValue, long limit, Microsoft.Azure.Management.Compute.Fluent.Models.UsageName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 currentValue, int64 limit, class Microsoft.Azure.Management.Compute.Fluent.Models.UsageName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.#ctor(System.Int32,System.Int64,Microsoft.Azure.Management.Compute.Fluent.Models.UsageName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (currentValue As Integer, limit As Long, name As UsageName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.Usage : int * int64 * Microsoft.Azure.Management.Compute.Fluent.Models.UsageName -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.Usage" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.Usage (currentValue, limit, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="currentValue" Type="System.Int32" />
        <Parameter Name="limit" Type="System.Int64" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Compute.Fluent.Models.UsageName" />
      </Parameters>
      <Docs>
        <param name="currentValue"><span data-ttu-id="a4bfe-103">リソースの現在の使用量。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-103">The current usage of the resource.</span></span></param>
        <param name="limit"><span data-ttu-id="a4bfe-104">最大値は、リソースの使用状況が許可されます。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-104">The maximum permitted usage of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a4bfe-105">使用法の種類の名前。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-105">The name of the type of usage.</span></span></param>
        <summary>
            <span data-ttu-id="a4bfe-106">使用状況のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-106">Initializes a new instance of the Usage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.Usage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4bfe-107">取得またはリソースの現在の使用量を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-107">Gets or sets the current usage of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public long Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Long" />
      <MemberSignature Language="F#" Value="member this.Limit : int64 with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="a4bfe-108">取得またはリソースの使用を許可される最大を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-108">Gets or sets the maximum permitted usage of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.UsageName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Compute.Fluent.Models.UsageName with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a4bfe-109">取得または使用法の種類の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-109">Gets or sets the name of the type of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public static string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="a4bfe-110">使用状況の測定単位を説明する列挙です。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-110">An enum describing the unit of usage measurement.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.Usage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usage.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a4bfe-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a4bfe-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a4bfe-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>