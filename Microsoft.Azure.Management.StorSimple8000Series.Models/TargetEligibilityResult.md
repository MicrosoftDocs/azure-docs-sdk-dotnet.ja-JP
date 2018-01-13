<Type Name="TargetEligibilityResult" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult">
  <TypeSignature Language="C#" Value="public class TargetEligibilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TargetEligibilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class TargetEligibilityResult" />
  <TypeSignature Language="F#" Value="type TargetEligibilityResult = class" />
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
            フェールオーバーのターゲット デバイスとして、デバイスの適格性結果。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TargetEligibilityResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityResult (Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; eligibilityStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; messages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; eligibilityStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.#ctor(System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eligibilityStatus As Nullable(Of TargetEligibilityStatus) = null, Optional messages As IList(Of TargetEligibilityErrorMessage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult (eligibilityStatus, messages)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eligibilityStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt;" />
        <Parameter Name="messages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="eligibilityStatus">フェールオーバーのターゲット デバイスとして、デバイスの適格性の状態。 使用可能な値が含まれます: 'NotEligible'、'有効'</param>
        <param name="messages">フェールオーバーのターゲット デバイスとして、デバイスが満たしていない場合、エラー メッセージの一覧。</param>
        <summary>
            TargetEligibilityResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EligibilityStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; EligibilityStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; EligibilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.EligibilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EligibilityStatus As Nullable(Of TargetEligibilityStatus)" />
      <MemberSignature Language="F#" Value="member this.EligibilityStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.EligibilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eligibilityStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフェールオーバーのターゲット デバイスとして、デバイスの適格性の状態を設定します。 使用可能な値が含まれます: 'NotEligible'、'有効'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Messages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; Messages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; Messages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.Messages" />
      <MemberSignature Language="VB.NET" Value="Public Property Messages As IList(Of TargetEligibilityErrorMessage)" />
      <MemberSignature Language="F#" Value="member this.Messages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResult.Messages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフェールオーバーのターゲット デバイスとして、デバイスが満たしていない場合に、エラー メッセージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>