<Type Name="RetentionPolicyParameters" FullName="Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters">
  <TypeSignature Language="C#" Value="public class RetentionPolicyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetentionPolicyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RetentionPolicyParameters" />
  <TypeSignature Language="F#" Value="type RetentionPolicyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6455c-101">フローのログの保持ポリシーを定義するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="6455c-101">Parameters that define the retention policy for flow log.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetentionPolicyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6455c-102">RetentionPolicyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6455c-102">Initializes a new instance of the RetentionPolicyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetentionPolicyParameters (Nullable&lt;int&gt; days = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; days, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.#ctor(System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional days As Nullable(Of Integer) = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters : Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters (days, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="days" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="days"><span data-ttu-id="6455c-103">フローのログ記録を保持する日数を指定します。</span><span class="sxs-lookup"><span data-stu-id="6455c-103">Number of days to retain flow log records.</span></span></param>
        <param name="enabled"><span data-ttu-id="6455c-104">保有期間の有効/無効にするフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="6455c-104">Flag to enable/disable retention.</span></span></param>
        <summary>
            <span data-ttu-id="6455c-105">RetentionPolicyParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6455c-105">Initializes a new instance of the RetentionPolicyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Days">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Days { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Days" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.Days" />
      <MemberSignature Language="VB.NET" Value="Public Property Days As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Days : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.Days" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="days")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6455c-106">取得またはフローのログ レコードを保持する日数を設定します。</span><span class="sxs-lookup"><span data-stu-id="6455c-106">Gets or sets number of days to retain flow log records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6455c-107">取得または保有期間の有効/無効にするフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="6455c-107">Gets or sets flag to enable/disable retention.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>