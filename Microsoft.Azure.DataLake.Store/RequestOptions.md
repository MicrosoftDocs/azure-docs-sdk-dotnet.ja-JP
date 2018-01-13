<Type Name="RequestOptions" FullName="Microsoft.Azure.DataLake.Store.RequestOptions">
  <TypeSignature Language="C#" Value="public class RequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestOptions" />
  <TypeSignature Language="F#" Value="type RequestOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスには、タイムアウト、再試行ポリシーおよび一意の requestId などの要求パラメーターが含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            初期化は、GUID、60 秒に、タイムアウトと再試行なしとして要求オプションとして Id を要求します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions (Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor(Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rp As RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RequestOptions : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy -&gt; Microsoft.Azure.DataLake.Store.RequestOptions" Usage="new Microsoft.Azure.DataLake.Store.RequestOptions rp" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rp" Type="Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="rp">オプションを再試行してください。</param>
        <summary>
            初期化します (既定値) の GUID、タイムアウトを 60 秒 (既定)、および要求オプションとして Id を要求します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions (string requestId, TimeSpan timeOut, Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string requestId, valuetype System.TimeSpan timeOut, class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor(System.String,System.TimeSpan,Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestId As String, timeOut As TimeSpan, rp As RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RequestOptions : string * TimeSpan * Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy -&gt; Microsoft.Azure.DataLake.Store.RequestOptions" Usage="new Microsoft.Azure.DataLake.Store.RequestOptions (requestId, timeOut, rp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestId" Type="System.String" />
        <Parameter Name="timeOut" Type="System.TimeSpan" />
        <Parameter Name="rp" Type="Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="requestId">要求 Id</param>
        <param name="timeOut">タイムアウト</param>
        <param name="rp">再試行ポリシー</param>
        <summary>
            初期化要求 Id、タイムアウト、および要求オプション
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一意の要求の Http 要求の Id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy RetryOption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy RetryOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.RetryOption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryOption As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryOption : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.RetryOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用する再試行ポリシーの種類
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeOut">
      <MemberSignature Language="C#" Value="public TimeSpan TimeOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.TimeOut" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeOut As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeOut : TimeSpan with get, set" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.TimeOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Http 要求のストリームの読み取りおよび書き込みのタイムアウト
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>