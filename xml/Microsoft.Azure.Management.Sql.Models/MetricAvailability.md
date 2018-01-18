<Type Name="MetricAvailability" FullName="Microsoft.Azure.Management.Sql.Models.MetricAvailability">
  <TypeSignature Language="C#" Value="public class MetricAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MetricAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricAvailability" />
  <TypeSignature Language="F#" Value="type MetricAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5accb-101">メトリックの可用性の値。</span><span class="sxs-lookup"><span data-stu-id="5accb-101">A metric availability value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5accb-102">MetricAvailability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5accb-102">Initializes a new instance of the MetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricAvailability (string retention = null, string timeGrain = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string retention, string timeGrain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricAvailability.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retention As String = null, Optional timeGrain As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MetricAvailability : string * string -&gt; Microsoft.Azure.Management.Sql.Models.MetricAvailability" Usage="new Microsoft.Azure.Management.Sql.Models.MetricAvailability (retention, timeGrain)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retention" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="retention"><span data-ttu-id="5accb-103">データベースのメトリックの保有期間の長さ。</span><span class="sxs-lookup"><span data-stu-id="5accb-103">The length of retention for the database metric.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="5accb-104">データベースのメトリックの粒度。</span><span class="sxs-lookup"><span data-stu-id="5accb-104">The granularity of the database metric.</span></span></param>
        <summary>
            <span data-ttu-id="5accb-105">MetricAvailability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5accb-105">Initializes a new instance of the MetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricAvailability.Retention" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricAvailability.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="5accb-106">データベースのメトリックの保有期間の長さを取得します。</span><span class="sxs-lookup"><span data-stu-id="5accb-106">Gets the length of retention for the database metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricAvailability.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricAvailability.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="5accb-107">データベースのメトリックの粒度を取得します。</span><span class="sxs-lookup"><span data-stu-id="5accb-107">Gets the granularity of the database metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>