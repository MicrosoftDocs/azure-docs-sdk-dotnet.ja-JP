<Type Name="ValidateResponseInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner">
  <TypeSignature Language="C#" Value="public class ValidateResponseInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateResponseInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateResponseInner" />
  <TypeSignature Language="F#" Value="type ValidateResponseInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92bee-101">リソースの検証の結果について説明します。</span><span class="sxs-lookup"><span data-stu-id="92bee-101">Describes the result of resource validation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponseInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92bee-102">ValidateResponseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92bee-102">Initializes a new instance of the ValidateResponseInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponseInner (string status = null, Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.#ctor(System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional error As ValidateResponseError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner : string * Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="92bee-103">検証の結果。</span><span class="sxs-lookup"><span data-stu-id="92bee-103">Result of validation.</span></span></param>
        <param name="error"><span data-ttu-id="92bee-104">検証が失敗した場合のエラーの詳細。</span><span class="sxs-lookup"><span data-stu-id="92bee-104">Error details for the case when validation fails.</span></span></param>
        <summary>
            <span data-ttu-id="92bee-105">ValidateResponseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92bee-105">Initializes a new instance of the ValidateResponseInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ValidateResponseError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92bee-106">取得または検証に失敗したときに大文字と小文字のエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="92bee-106">Gets or sets error details for the case when validation fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ValidateResponseInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92bee-107">取得または検証の結果を設定します。</span><span class="sxs-lookup"><span data-stu-id="92bee-107">Gets or sets result of validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>