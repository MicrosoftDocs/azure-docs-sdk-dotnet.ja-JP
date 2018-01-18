<Type Name="NoRetry" FullName="Microsoft.Azure.Devices.Client.NoRetry">
  <TypeSignature Language="C#" Value="public class NoRetry : Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NoRetry extends System.Object implements class Microsoft.Azure.Devices.Client.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.NoRetry" />
  <TypeSignature Language="VB.NET" Value="Public Class NoRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetry = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="49e60-101">実行再試行再試行ポリシーを表しません。</span><span class="sxs-lookup"><span data-stu-id="49e60-101">Represents a retry policy that performs no retries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.NoRetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, Exception lastException, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.NoRetry.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Public Function ShouldRetry (currentRetryCount As Integer, lastException As Exception, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * Exception *  -&gt; bool&#xA;override this.ShouldRetry : int * Exception *  -&gt; bool" Usage="noRetry.ShouldRetry (currentRetryCount, lastException, retryInterval)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.Client.IRetryPolicy.ShouldRetry(System.Int32,System.Exception,System.TimeSpan@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount">To be added.</param>
        <param name="lastException">To be added.</param>
        <param name="retryInterval">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>