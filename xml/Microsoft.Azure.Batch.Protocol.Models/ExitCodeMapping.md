<Type Name="ExitCodeMapping" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeMapping = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="36323-101">方法は、バッチ サービスで、タスクが、特定の終了コードで終了したかどうかを応答します。</span><span class="sxs-lookup"><span data-stu-id="36323-101">How the Batch service should respond if a task exits with a particular exit code.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36323-102">ExitCodeMapping クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36323-102">Initializes a new instance of the ExitCodeMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeMapping (int code, Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 code, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.#ctor(System.Int32,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping : int * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping (code, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="36323-103">プロセス終了コード。</span><span class="sxs-lookup"><span data-stu-id="36323-103">A process exit code.</span></span></param>
        <param name="exitOptions"><span data-ttu-id="36323-104">方法は、バッチ サービスで、タスクがこの終了コードで終了したかどうかを応答します。</span><span class="sxs-lookup"><span data-stu-id="36323-104">How the Batch service should respond if the task exits with this exit code.</span></span></param>
        <summary>
            <span data-ttu-id="36323-105">ExitCodeMapping クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36323-105">Initializes a new instance of the ExitCodeMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public int Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As Integer" />
      <MemberSignature Language="F#" Value="member this.Code : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36323-106">取得またはプロセス終了コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="36323-106">Gets or sets a process exit code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36323-107">取得または終了コードはこのタスクが終了した場合、バッチ サービスの応答方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="36323-107">Gets or sets how the Batch service should respond if the task exits with this exit code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exitCodeMapping.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36323-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="36323-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="36323-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36323-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>