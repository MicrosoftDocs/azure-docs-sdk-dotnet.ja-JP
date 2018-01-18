<Type Name="CsmMoveResourceEnvelopeInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner">
  <TypeSignature Language="C#" Value="public class CsmMoveResourceEnvelopeInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsmMoveResourceEnvelopeInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CsmMoveResourceEnvelopeInner" />
  <TypeSignature Language="F#" Value="type CsmMoveResourceEnvelopeInner = class" />
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
            <span data-ttu-id="5ef59-101">移動する必要があるリソースの一覧を持つオブジェクトとリソース グループに移動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5ef59-101">Object with a list of the resources that need to be moved and the resource group they should be moved to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmMoveResourceEnvelopeInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ef59-102">CsmMoveResourceEnvelopeInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5ef59-102">Initializes a new instance of the CsmMoveResourceEnvelopeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmMoveResourceEnvelopeInner (string targetResourceGroup = null, System.Collections.Generic.IList&lt;string&gt; resources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceGroup, class System.Collections.Generic.IList`1&lt;string&gt; resources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional targetResourceGroup As String = null, Optional resources As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner (targetResourceGroup, resources)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceGroup" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="targetResourceGroup">To be added.</param>
        <param name="resources">To be added.</param>
        <summary>
            <span data-ttu-id="5ef59-103">CsmMoveResourceEnvelopeInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5ef59-103">Initializes a new instance of the CsmMoveResourceEnvelopeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroup">
      <MemberSignature Language="C#" Value="public string TargetResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.TargetResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.TargetResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmMoveResourceEnvelopeInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="csmMoveResourceEnvelopeInner.Validate " />
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
            <span data-ttu-id="5ef59-104">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5ef59-104">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5ef59-105">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5ef59-105">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>