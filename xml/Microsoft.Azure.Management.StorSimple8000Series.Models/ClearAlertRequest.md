<Type Name="ClearAlertRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest">
  <TypeSignature Language="C#" Value="public class ClearAlertRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClearAlertRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ClearAlertRequest" />
  <TypeSignature Language="F#" Value="type ClearAlertRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cac40-101">アラートをクリアするための要求</span><span class="sxs-lookup"><span data-stu-id="cac40-101">The request for clearing the alert</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClearAlertRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cac40-102">ClearAlertRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cac40-102">Initializes a new instance of the ClearAlertRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClearAlertRequest (System.Collections.Generic.IList&lt;string&gt; alerts, string resolutionMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; alerts, string resolutionMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (alerts As IList(Of String), Optional resolutionMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest (alerts, resolutionMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="alerts" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resolutionMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="alerts"><span data-ttu-id="cac40-103">削除する警告 Id の一覧</span><span class="sxs-lookup"><span data-stu-id="cac40-103">The list of alert IDs to be cleared</span></span></param>
        <param name="resolutionMessage"><span data-ttu-id="cac40-104">アラートの消去中に解決メッセージ</span><span class="sxs-lookup"><span data-stu-id="cac40-104">The resolution message while clearing the alert</span></span></param>
        <summary>
            <span data-ttu-id="cac40-105">ClearAlertRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cac40-105">Initializes a new instance of the ClearAlertRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alerts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Alerts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Alerts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.Alerts" />
      <MemberSignature Language="VB.NET" Value="Public Property Alerts As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Alerts : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.Alerts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="alerts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cac40-106">取得またはアラートをクリアする Id の一覧の設定</span><span class="sxs-lookup"><span data-stu-id="cac40-106">Gets or sets the list of alert IDs to be cleared</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolutionMessage">
      <MemberSignature Language="C#" Value="public string ResolutionMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResolutionMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.ResolutionMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolutionMessage As String" />
      <MemberSignature Language="F#" Value="member this.ResolutionMessage : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.ResolutionMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolutionMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cac40-107">取得またはアラートの消去中に、解像度のメッセージを設定</span><span class="sxs-lookup"><span data-stu-id="cac40-107">Gets or sets the resolution message while clearing the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clearAlertRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cac40-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="cac40-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac40-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac40-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>