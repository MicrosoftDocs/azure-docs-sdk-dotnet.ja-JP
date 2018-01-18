<Type Name="RuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition">
  <TypeSignature Language="C#" Value="public class RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleCondition" />
  <TypeSignature Language="F#" Value="type RuleCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="afa0f-101">アラートのルールがアクティブ化される条件。</span><span class="sxs-lookup"><span data-stu-id="afa0f-101">The condition that results in the alert rule being activated.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="afa0f-102">RuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="afa0f-102">Initializes a new instance of the RuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleCondition (Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSource As RuleDataSource = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition dataSource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
      </Parameters>
      <Docs>
        <param name="dataSource"><span data-ttu-id="afa0f-103">ルールがそのデータを収集元となるリソースです。</span><span class="sxs-lookup"><span data-stu-id="afa0f-103">the resource from which the rule collects its data.</span></span> <span data-ttu-id="afa0f-104">この種類のデータ ソースが必ず型 RuleMetricDataSource の。</span><span class="sxs-lookup"><span data-stu-id="afa0f-104">For this type dataSource will always be of type RuleMetricDataSource.</span></span></param>
        <summary>
            <span data-ttu-id="afa0f-105">RuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="afa0f-105">Initializes a new instance of the RuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource DataSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSource As RuleDataSource" />
      <MemberSignature Language="F#" Value="member this.DataSource : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition.DataSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afa0f-106">取得またはルールがそのデータを収集元となるリソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="afa0f-106">Gets or sets the resource from which the rule collects its data.</span></span>
            <span data-ttu-id="afa0f-107">この種類のデータ ソースが必ず型 RuleMetricDataSource の。</span><span class="sxs-lookup"><span data-stu-id="afa0f-107">For this type dataSource will always be of type RuleMetricDataSource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>