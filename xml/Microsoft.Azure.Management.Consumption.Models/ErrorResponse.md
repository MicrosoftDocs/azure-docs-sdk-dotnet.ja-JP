<Type Name="ErrorResponse" FullName="Microsoft.Azure.Management.Consumption.Models.ErrorResponse">
  <TypeSignature Language="C#" Value="public class ErrorResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.Models.ErrorResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponse" />
  <TypeSignature Language="F#" Value="type ErrorResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42847-101">エラー応答は、サービスが受信要求を処理できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="42847-101">Error response indicates that the service is not able to process the incoming request.</span></span> <span data-ttu-id="42847-102">その理由は、エラー メッセージで提供されます。</span><span class="sxs-lookup"><span data-stu-id="42847-102">The reason is provided in the error message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42847-103">ErrorResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42847-103">Initializes a new instance of the ErrorResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse (Microsoft.Azure.Management.Consumption.Models.ErrorDetails error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Consumption.Models.ErrorDetails error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.#ctor(Microsoft.Azure.Management.Consumption.Models.ErrorDetails)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional error As ErrorDetails = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Consumption.Models.ErrorResponse : Microsoft.Azure.Management.Consumption.Models.ErrorDetails -&gt; Microsoft.Azure.Management.Consumption.Models.ErrorResponse" Usage="new Microsoft.Azure.Management.Consumption.Models.ErrorResponse error" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="error" Type="Microsoft.Azure.Management.Consumption.Models.ErrorDetails" />
      </Parameters>
      <Docs>
        <param name="error"><span data-ttu-id="42847-104">エラーの詳細。</span><span class="sxs-lookup"><span data-stu-id="42847-104">The details of the error.</span></span></param>
        <summary>
            <span data-ttu-id="42847-105">ErrorResponse クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42847-105">Initializes a new instance of the ErrorResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Consumption.Models.ErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Consumption.Models.ErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.ErrorResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Consumption.Models.ErrorDetails with get, set" Usage="Microsoft.Azure.Management.Consumption.Models.ErrorResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Consumption.Models.ErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42847-106">取得またはエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="42847-106">Gets or sets the details of the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>