<Type Name="PoolUpgradeOSParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter">
  <TypeSignature Language="C#" Value="public class PoolUpgradeOSParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUpgradeOSParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUpgradeOSParameter" />
  <TypeSignature Language="F#" Value="type PoolUpgradeOSParameter = class" />
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
            <span data-ttu-id="84f31-101">オペレーティング システムをアップグレードするためのオプションは、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="84f31-101">Options for upgrading the operating system of compute nodes in a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpgradeOSParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter.#ctor" />
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
            <span data-ttu-id="84f31-102">PoolUpgradeOSParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="84f31-102">Initializes a new instance of the PoolUpgradeOSParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpgradeOSParameter (string targetOSVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetOSVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetOSVersion As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter : string -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter targetOSVersion" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetOSVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetOSVersion"><span data-ttu-id="84f31-103">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</span><span class="sxs-lookup"><span data-stu-id="84f31-103">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <summary>
            <span data-ttu-id="84f31-104">PoolUpgradeOSParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="84f31-104">Initializes a new instance of the PoolUpgradeOSParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetOSVersion">
      <MemberSignature Language="C#" Value="public string TargetOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter.TargetOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetOSVersion : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter.TargetOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84f31-105">取得またはプール内の仮想マシンにインストールされている Azure ゲスト OS バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="84f31-105">Gets or sets the Azure Guest OS version to be installed on the virtual machines in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolUpgradeOSParameter.Validate " />
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
            <span data-ttu-id="84f31-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="84f31-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="84f31-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="84f31-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>