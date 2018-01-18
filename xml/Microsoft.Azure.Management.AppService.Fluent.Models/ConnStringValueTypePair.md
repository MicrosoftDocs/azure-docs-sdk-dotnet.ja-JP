<Type Name="ConnStringValueTypePair" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair">
  <TypeSignature Language="C#" Value="public class ConnStringValueTypePair" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnStringValueTypePair extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnStringValueTypePair" />
  <TypeSignature Language="F#" Value="type ConnStringValueTypePair = class" />
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
            <span data-ttu-id="6efa7-101">接続文字列値をデータベースのペアを入力します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-101">Database connection string value to type pair.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6efa7-102">ConnStringValueTypePair クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-102">Initializes a new instance of the ConnStringValueTypePair class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair (string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.#ctor(System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As String, type As ConnectionStringType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair : string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair (value, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="6efa7-103">ペアの値です。</span><span class="sxs-lookup"><span data-stu-id="6efa7-103">Value of pair.</span></span></param>
        <param name="type"><span data-ttu-id="6efa7-104">データベースの種類。</span><span class="sxs-lookup"><span data-stu-id="6efa7-104">Type of database.</span></span> <span data-ttu-id="6efa7-105">使用可能な値が含まれます: 'MySql'、'SQLServer'、'SQLAzure'、'Custom'、'NotificationHub'、'ServiceBus'、'EventHub'、'ApiHub'、'DocDb'、'RedisCache'</span><span class="sxs-lookup"><span data-stu-id="6efa7-105">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache'</span></span></param>
        <summary>
            <span data-ttu-id="6efa7-106">ConnStringValueTypePair クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-106">Initializes a new instance of the ConnStringValueTypePair class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ConnectionStringType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6efa7-107">取得またはデータベースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-107">Gets or sets type of database.</span></span> <span data-ttu-id="6efa7-108">使用可能な値が含まれます: 'MySql'、'SQLServer'、'SQLAzure'、'Custom'、'NotificationHub'、'ServiceBus'、'EventHub'、'ApiHub'、'DocDb'、'RedisCache'</span><span class="sxs-lookup"><span data-stu-id="6efa7-108">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connStringValueTypePair.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6efa7-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6efa7-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6efa7-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringValueTypePair.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6efa7-111">取得またはペアの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6efa7-111">Gets or sets value of pair.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>