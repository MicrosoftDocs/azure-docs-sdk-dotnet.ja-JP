<Type Name="ExponentialRetryPolicy" FullName="Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy">
  <TypeSignature Language="C#" Value="public class ExponentialRetryPolicy : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialRetryPolicy extends Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialRetryPolicy&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialRetryPolicy = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            指数近似の再試行ポリシー
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.#ctor" />
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
            指数近似の再試行ポリシーの既定の設定
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetryPolicy (int maxRetries, int interval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maxRetries, int32 interval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxRetries As Integer, interval As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy : int * int -&gt; Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy" Usage="new Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy (maxRetries, interval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxRetries" Type="System.Int32" />
        <Parameter Name="interval" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxRetries">最大再試行回数</param>
        <param name="interval">指数の時間間隔</param>
        <summary>
            指定した最大再試行回数と間隔が指数近似の再試行ポリシー
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public override bool ShouldRetry (int httpCode, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool ShouldRetry(int32 httpCode, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.ExponentialRetryPolicy.ShouldRetry(System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ShouldRetry (httpCode As Integer, ex As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.ShouldRetry : int * Exception -&gt; bool" Usage="exponentialRetryPolicy.ShouldRetry (httpCode, ex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpCode" Type="System.Int32" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="httpCode">Http 状態コード</param>
        <param name="ex">Httprequest 中見た最後の例外</param>
        <summary>
            指数関数的に再試行するかどうか
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>