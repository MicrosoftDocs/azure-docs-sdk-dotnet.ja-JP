<Type Name="StoredProcedureParameter" FullName="Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter">
  <TypeSignature Language="C#" Value="public class StoredProcedureParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StoredProcedureParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class StoredProcedureParameter" />
  <TypeSignature Language="F#" Value="type StoredProcedureParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="520d7-101">SQL では、プロシージャのパラメーターを格納します。</span><span class="sxs-lookup"><span data-stu-id="520d7-101">SQL stored procedure parameter.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoredProcedureParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="520d7-102">ストアド プロシージャ パラメーター クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="520d7-102">Initializes a new instance of the StoredProcedureParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StoredProcedureParameter (object value, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object value, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.#ctor(System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As Object, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter : obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter" Usage="new Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter (value, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="520d7-103">ストアド プロシージャ パラメーターの値です。</span><span class="sxs-lookup"><span data-stu-id="520d7-103">Stored procedure parameter value.</span></span> <span data-ttu-id="520d7-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="520d7-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="type"><span data-ttu-id="520d7-105">ストアド プロシージャ パラメーターの型。</span><span class="sxs-lookup"><span data-stu-id="520d7-105">Stored procedure parameter type.</span></span> <span data-ttu-id="520d7-106">使用可能な値が含まれます: 'String'、'Int'、'Decimal'、'Guid'、'Boolean'、'Date'</span><span class="sxs-lookup"><span data-stu-id="520d7-106">Possible values include: 'String', 'Int', 'Decimal', 'Guid', 'Boolean', 'Date'</span></span></param>
        <summary>
            <span data-ttu-id="520d7-107">ストアド プロシージャ パラメーター クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="520d7-107">Initializes a new instance of the StoredProcedureParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="520d7-108">取得またはストアド プロシージャ パラメーターの型を設定します。</span><span class="sxs-lookup"><span data-stu-id="520d7-108">Gets or sets stored procedure parameter type.</span></span> <span data-ttu-id="520d7-109">使用可能な値が含まれます: 'String'、'Int'、'Decimal'、'Guid'、'Boolean'、'Date'</span><span class="sxs-lookup"><span data-stu-id="520d7-109">Possible values include: 'String', 'Int', 'Decimal', 'Guid', 'Boolean', 'Date'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storedProcedureParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="520d7-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="520d7-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="520d7-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="520d7-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="520d7-112">取得またはストアド プロシージャのパラメーター値を設定します。</span><span class="sxs-lookup"><span data-stu-id="520d7-112">Gets or sets stored procedure parameter value.</span></span> <span data-ttu-id="520d7-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="520d7-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>