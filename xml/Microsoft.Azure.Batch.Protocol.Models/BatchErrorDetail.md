<Type Name="BatchErrorDetail" FullName="Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail">
  <TypeSignature Language="C#" Value="public class BatchErrorDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchErrorDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchErrorDetail" />
  <TypeSignature Language="F#" Value="type BatchErrorDetail = class" />
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
            <span data-ttu-id="b7bb8-101">Azure Batch のエラー応答に含まれる追加の情報の項目です。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-101">An item of additional information included in an Azure Batch error response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchErrorDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.#ctor" />
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
            <span data-ttu-id="b7bb8-102">BatchErrorDetail クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-102">Initializes a new instance of the BatchErrorDetail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchErrorDetail (string key = null, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional key As String = null, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail" Usage="new Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail (key, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="b7bb8-103">Value プロパティの意味を指定する識別子。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-103">An identifier specifying the meaning of the Value property.</span></span></param>
        <param name="value"><span data-ttu-id="b7bb8-104">エラー応答に含まれている追加情報。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-104">The additional information included with the error response.</span></span></param>
        <summary>
            <span data-ttu-id="b7bb8-105">BatchErrorDetail クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-105">Initializes a new instance of the BatchErrorDetail class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb8-106">取得または Value プロパティの意味を指定する識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-106">Gets or sets an identifier specifying the meaning of the Value property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7bb8-107">取得またはエラー応答に含まれている追加の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="b7bb8-107">Gets or sets the additional information included with the error response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>