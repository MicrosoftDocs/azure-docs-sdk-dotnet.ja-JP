<Type Name="LifetimeAction" FullName="Microsoft.Azure.KeyVault.Models.LifetimeAction">
  <TypeSignature Language="C#" Value="public class LifetimeAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LifetimeAction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.LifetimeAction" />
  <TypeSignature Language="VB.NET" Value="Public Class LifetimeAction" />
  <TypeSignature Language="F#" Value="type LifetimeAction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2f3df-101">アクションとその証明書の有効期間にわたって Key Vault によって実行されるトリガー。</span><span class="sxs-lookup"><span data-stu-id="2f3df-101">Action and its trigger that will be performed by Key Vault over the lifetime of a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LifetimeAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.LifetimeAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2f3df-102">LifetimeAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2f3df-102">Initializes a new instance of the LifetimeAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LifetimeAction (Microsoft.Azure.KeyVault.Models.Trigger trigger = null, Microsoft.Azure.KeyVault.Models.Action action = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.Models.Trigger trigger, class Microsoft.Azure.KeyVault.Models.Action action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.LifetimeAction.#ctor(Microsoft.Azure.KeyVault.Models.Trigger,Microsoft.Azure.KeyVault.Models.Action)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.LifetimeAction : Microsoft.Azure.KeyVault.Models.Trigger * Microsoft.Azure.KeyVault.Models.Action -&gt; Microsoft.Azure.KeyVault.Models.LifetimeAction" Usage="new Microsoft.Azure.KeyVault.Models.LifetimeAction (trigger, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="trigger" Type="Microsoft.Azure.KeyVault.Models.Trigger" />
        <Parameter Name="action" Type="Microsoft.Azure.KeyVault.Models.Action" />
      </Parameters>
      <Docs>
        <param name="trigger"><span data-ttu-id="2f3df-103">アクションを実行する条件。</span><span class="sxs-lookup"><span data-stu-id="2f3df-103">The condition that will execute the action.</span></span></param>
        <param name="action"><span data-ttu-id="2f3df-104">実行されるアクション。</span><span class="sxs-lookup"><span data-stu-id="2f3df-104">The action that will be executed.</span></span></param>
        <summary>
            <span data-ttu-id="2f3df-105">LifetimeAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2f3df-105">Initializes a new instance of the LifetimeAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.Action Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.Action Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.LifetimeAction.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As Action" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.KeyVault.Models.Action with get, set" Usage="Microsoft.Azure.KeyVault.Models.LifetimeAction.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.Action</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f3df-106">取得または実行されるアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="2f3df-106">Gets or sets the action that will be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.Trigger Trigger { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.Trigger Trigger" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.LifetimeAction.Trigger" />
      <MemberSignature Language="VB.NET" Value="Public Property Trigger As Trigger" />
      <MemberSignature Language="F#" Value="member this.Trigger : Microsoft.Azure.KeyVault.Models.Trigger with get, set" Usage="Microsoft.Azure.KeyVault.Models.LifetimeAction.Trigger" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="trigger")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.Trigger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f3df-107">取得またはアクションを実行する条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f3df-107">Gets or sets the condition that will execute the action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.LifetimeAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="lifetimeAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2f3df-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2f3df-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2f3df-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2f3df-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>