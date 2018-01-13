<Type Name="SlowRequestsBasedTrigger" FullName="Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger">
  <TypeSignature Language="C#" Value="public class SlowRequestsBasedTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SlowRequestsBasedTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class SlowRequestsBasedTrigger" />
  <TypeSignature Language="F#" Value="type SlowRequestsBasedTrigger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            要求の実行時刻に基づいてトリガーします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlowRequestsBasedTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SlowRequestsBasedTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlowRequestsBasedTrigger (string timeTaken = null, Nullable&lt;int&gt; count = null, string timeInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeTaken, valuetype System.Nullable`1&lt;int32&gt; count, string timeInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.#ctor(System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeTaken As String = null, Optional count As Nullable(Of Integer) = null, Optional timeInterval As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger : string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger" Usage="new Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger (timeTaken, count, timeInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeTaken" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeInterval" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeTaken">かかった時間です。</param>
        <param name="count">カウントです。</param>
        <param name="timeInterval">時間間隔。</param>
        <summary>
            SlowRequestsBasedTrigger クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeInterval">
      <MemberSignature Language="C#" Value="public string TimeInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.TimeInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeInterval As String" />
      <MemberSignature Language="F#" Value="member this.TimeInterval : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.TimeInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間間隔を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeTaken">
      <MemberSignature Language="C#" Value="public string TimeTaken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeTaken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.TimeTaken" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeTaken As String" />
      <MemberSignature Language="F#" Value="member this.TimeTaken : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SlowRequestsBasedTrigger.TimeTaken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeTaken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定にかかった時間。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>