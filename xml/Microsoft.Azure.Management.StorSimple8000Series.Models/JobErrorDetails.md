<Type Name="JobErrorDetails" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails">
  <TypeSignature Language="C#" Value="public class JobErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class JobErrorDetails" />
  <TypeSignature Language="F#" Value="type JobErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="77dde-101">ジョブ エラーの詳細。</span><span class="sxs-lookup"><span data-stu-id="77dde-101">The job error details.</span></span> <span data-ttu-id="77dde-102">ジョブのエラー項目の一覧が含まれています。</span><span class="sxs-lookup"><span data-stu-id="77dde-102">Contains list of job error items.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77dde-103">JobErrorDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77dde-103">Initializes a new instance of the JobErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobErrorDetails (string code, string message, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; errorDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; errorDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional errorDetails As IList(Of JobErrorItem) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails (code, message, errorDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="77dde-104">エラー コードは、プログラムによるアクセスを目的としています。</span><span class="sxs-lookup"><span data-stu-id="77dde-104">The error code intended for programmatic access.</span></span></param>
        <param name="message"><span data-ttu-id="77dde-105">エラー メッセージは、エラーの詳細を記述する目的としています。</span><span class="sxs-lookup"><span data-stu-id="77dde-105">The error message intended to describe the error in detail.</span></span></param>
        <param name="errorDetails"><span data-ttu-id="77dde-106">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="77dde-106">The error details.</span></span></param>
        <summary>
            <span data-ttu-id="77dde-107">JobErrorDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77dde-107">Initializes a new instance of the JobErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77dde-108">取得またはプログラムによるアクセスのためのもので、エラー コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="77dde-108">Gets or sets the error code intended for programmatic access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of JobErrorItem)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77dde-109">取得またはエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="77dde-109">Gets or sets the error details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="77dde-110">取得またはエラーの詳細を記述するためのもので、エラー メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="77dde-110">Gets or sets the error message intended to describe the error in detail.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobErrorDetails.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77dde-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="77dde-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="77dde-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="77dde-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>