<Type Name="UpdateIntegrationRuntimeRequest" FullName="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest">
  <TypeSignature Language="C#" Value="public class UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateIntegrationRuntimeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="F#" Value="type UpdateIntegrationRuntimeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            統合ランタイム要求を更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UpdateIntegrationRuntimeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeRequest (string autoUpdate = null, string updateDelayOffset = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string autoUpdate, string updateDelayOffset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional autoUpdate As String = null, Optional updateDelayOffset As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest : string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" Usage="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest (autoUpdate, updateDelayOffset)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoUpdate" Type="System.String" />
        <Parameter Name="updateDelayOffset" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="autoUpdate">有効または自己ホスト型の統合の実行時の自動更新機能を無効にします。 Https://go.microsoft.com/fwlink/?linkid=854189 を参照してください。 使用可能な値が含まれます 'On'、'Off'。</param>
        <param name="updateDelayOffset">オフセット (時間) の日付、時刻など、PT03H は 3 時間です。 統合ランタイムの自動更新は、その時間に実行されます。</param>
        <summary>
            UpdateIntegrationRuntimeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUpdate">
      <MemberSignature Language="C#" Value="public string AutoUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoUpdate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.AutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUpdate As String" />
      <MemberSignature Language="F#" Value="member this.AutoUpdate : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.AutoUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoUpdate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を有効または自己ホスト型の統合の実行時の自動更新機能を無効にします。 Https://go.microsoft.com/fwlink/?linkid=854189 を参照してください。 使用可能な値が含まれます 'On'、'Off'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDelayOffset">
      <MemberSignature Language="C#" Value="public string UpdateDelayOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateDelayOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.UpdateDelayOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateDelayOffset As String" />
      <MemberSignature Language="F#" Value="member this.UpdateDelayOffset : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.UpdateDelayOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updateDelayOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が、時間のオフセット (時間) を PT03H などの日付が 3 時間です。 統合ランタイムの自動更新は、その時間に実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>