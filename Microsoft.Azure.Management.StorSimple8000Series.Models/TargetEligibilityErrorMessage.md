<Type Name="TargetEligibilityErrorMessage" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage">
  <TypeSignature Language="C#" Value="public class TargetEligibilityErrorMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TargetEligibilityErrorMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class TargetEligibilityErrorMessage" />
  <TypeSignature Language="F#" Value="type TargetEligibilityErrorMessage = class" />
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
            これにより、デバイスが不適格であるフェールオーバー ターゲット デバイスとしてエラー/警告メッセージ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityErrorMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TargetEligibilityErrorMessage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TargetEligibilityErrorMessage (string message = null, string resolution = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; resultCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, string resolution, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; resultCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional message As String = null, Optional resolution As String = null, Optional resultCode As Nullable(Of TargetEligibilityResultCode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage : string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage (message, resolution, resultCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="resultCode" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt;" />
      </Parameters>
      <Docs>
        <param name="message">デバイスが対象となるデバイスとして対象となる理由を示すローカライズされたエラー メッセージ。</param>
        <param name="resolution">エラーの解決のローカライズされたメッセージです。</param>
        <param name="resultCode">フェールオーバーのターゲット デバイスとして扱われませんデバイス原因になったエラーの結果コード。
            使用可能な値が含まれます: 'TargetAndSourceCannotBeSameError'、'TargetIsNotOnlineError'、'TargetSourceIncompatibleVersionError'、'LocalToTieredVolumesConversionWarning'、'TargetInsufficientCapacityError'、'TargetInsufficientLocalVolumeMemoryError'、'TargetInsufficientTieredVolumeMemoryError'</param>
        <summary>
            TargetEligibilityErrorMessage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスが対象となるデバイスとして対象となる理由を示すローカライズされたエラー メッセージを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエラーのメッセージをローカライズされた解像度を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; ResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; ResultCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.ResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCode As Nullable(Of TargetEligibilityResultCode)" />
      <MemberSignature Language="F#" Value="member this.ResultCode : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityErrorMessage.ResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resultCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.TargetEligibilityResultCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定したエラーの原因になったは、デバイスは、フェールオーバーのターゲット デバイスとして扱われません結果コード。 使用可能な値が含まれます: 'TargetAndSourceCannotBeSameError'、'TargetIsNotOnlineError'、'TargetSourceIncompatibleVersionError'、'LocalToTieredVolumesConversionWarning'、'TargetInsufficientCapacityError'、'TargetInsufficientLocalVolumeMemoryError'、'TargetInsufficientTieredVolumeMemoryError'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>