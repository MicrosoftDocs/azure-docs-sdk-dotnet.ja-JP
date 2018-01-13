<Type Name="CsmSlotEntityInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner">
  <TypeSignature Language="C#" Value="public class CsmSlotEntityInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsmSlotEntityInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CsmSlotEntityInner" />
  <TypeSignature Language="F#" Value="type CsmSlotEntityInner = class" />
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
            デプロイ スロットのパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmSlotEntityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CsmSlotEntityInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmSlotEntityInner (string targetSlot, bool preserveVnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetSlot, bool preserveVnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetSlot As String, preserveVnet As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner (targetSlot, preserveVnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetSlot" Type="System.String" />
        <Parameter Name="preserveVnet" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="targetSlot">スワップ操作中に移行先のデプロイ スロット。</param>
        <param name="preserveVnet">&lt;コード&gt;true&lt;/code&gt;スロットにスワップ; 中に仮想ネットワークを保持するためにそれ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <summary>
            CsmSlotEntityInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveVnet">
      <MemberSignature Language="C#" Value="public bool PreserveVnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PreserveVnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.PreserveVnet" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveVnet As Boolean" />
      <MemberSignature Language="F#" Value="member this.PreserveVnet : bool with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.PreserveVnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveVnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; のスロットにスワップ; 中に仮想ネットワークを保持するためにそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSlot">
      <MemberSignature Language="C#" Value="public string TargetSlot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.TargetSlot" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSlot : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.TargetSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスワップ操作中に移行先のデプロイ スロットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="csmSlotEntityInner.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>