<Type Name="MetricAvailabilily" FullName="Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily">
  <TypeSignature Language="C#" Value="public class MetricAvailabilily" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailabilily extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailabilily" />
  <TypeSignature Language="F#" Value="type MetricAvailabilily = class" />
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
            <span data-ttu-id="4e20d-101">メトリックの可用性と保有期間。</span><span class="sxs-lookup"><span data-stu-id="4e20d-101">Metric availability and retention.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailabilily ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e20d-102">MetricAvailabilily クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e20d-102">Initializes a new instance of the MetricAvailabilily class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailabilily (string timeGrain = null, string retention = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeGrain, string retention) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As String = null, Optional retention As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily : string * string -&gt; Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily" Usage="new Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily (timeGrain, retention)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="retention" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeGrain"><span data-ttu-id="4e20d-103">時間の単位。</span><span class="sxs-lookup"><span data-stu-id="4e20d-103">Time grain.</span></span></param>
        <param name="retention"><span data-ttu-id="4e20d-104">現在の時間グレインの保有期間。</span><span class="sxs-lookup"><span data-stu-id="4e20d-104">Retention period for the current time grain.</span></span></param>
        <summary>
            <span data-ttu-id="4e20d-105">MetricAvailabilily クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e20d-105">Initializes a new instance of the MetricAvailabilily class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4e20d-106">取得または現在の時間グレインの保有期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="4e20d-106">Gets or sets retention period for the current time grain.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4e20d-107">取得または時間の単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="4e20d-107">Gets or sets time grain.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>