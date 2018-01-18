<Type Name="AutoHealRules" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules">
  <TypeSignature Language="C#" Value="public class AutoHealRules" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoHealRules extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoHealRules" />
  <TypeSignature Language="F#" Value="type AutoHealRules = class" />
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
            <span data-ttu-id="c0d18-101">に対して定義できるルールの自動-回復します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-101">Rules that can be defined for auto-heal.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealRules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c0d18-102">AutoHealRules クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-102">Initializes a new instance of the AutoHealRules class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealRules (Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers triggers = null, Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions actions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers triggers, class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions actions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.#ctor(Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers,Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional triggers As AutoHealTriggers = null, Optional actions As AutoHealActions = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules : Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers * Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules (triggers, actions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="triggers" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers" />
        <Parameter Name="actions" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions" />
      </Parameters>
      <Docs>
        <param name="triggers"><span data-ttu-id="c0d18-103">実行する場合を説明する条件、アクションを自動修復します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-103">Conditions that describe when to execute the auto-heal actions.</span></span></param>
        <param name="actions"><span data-ttu-id="c0d18-104">ルールがトリガーされたときに実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="c0d18-104">Actions to be executed when a rule is triggered.</span></span></param>
        <summary>
            <span data-ttu-id="c0d18-105">AutoHealRules クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-105">Initializes a new instance of the AutoHealRules class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Actions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions Actions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions Actions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.Actions" />
      <MemberSignature Language="VB.NET" Value="Public Property Actions As AutoHealActions" />
      <MemberSignature Language="F#" Value="member this.Actions : Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.Actions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealActions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0d18-106">取得またはルールがトリガーされたときに実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-106">Gets or sets actions to be executed when a rule is triggered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Triggers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers Triggers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers Triggers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.Triggers" />
      <MemberSignature Language="VB.NET" Value="Public Property Triggers As AutoHealTriggers" />
      <MemberSignature Language="F#" Value="member this.Triggers : Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules.Triggers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealTriggers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0d18-107">取得または設定を実行する場合を説明する条件、アクションを自動修復します。</span><span class="sxs-lookup"><span data-stu-id="c0d18-107">Gets or sets conditions that describe when to execute the auto-heal actions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>