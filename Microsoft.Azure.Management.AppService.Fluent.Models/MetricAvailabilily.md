<Type Name="MetricAvailabilily" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily">
  <TypeSignature Language="C#" Value="public class MetricAvailabilily" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailabilily extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailabilily" />
  <TypeSignature Language="F#" Value="type MetricAvailabilily = class" />
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
            メトリックの可用性と保有期間。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailabilily ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MetricAvailabilily クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailabilily (string timeGrain = null, string retention = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeGrain, string retention) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As String = null, Optional retention As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily (timeGrain, retention)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="retention" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeGrain">時間の単位。</param>
        <param name="retention">現在の時間グレインの保有期間。</param>
        <summary>
            MetricAvailabilily クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在の時間グレインの保有期間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.MetricAvailabilily.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時間の単位を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>