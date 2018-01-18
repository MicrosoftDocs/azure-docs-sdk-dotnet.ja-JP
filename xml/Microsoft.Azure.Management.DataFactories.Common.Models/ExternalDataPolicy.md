<Type Name="ExternalDataPolicy" FullName="Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy">
  <TypeSignature Language="C#" Value="public class ExternalDataPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExternalDataPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ExternalDataPolicy" />
  <TypeSignature Language="F#" Value="type ExternalDataPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b9bc-101">外部データの検証と再試行ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-101">External data validation and retry policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalDataPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b9bc-102">ExternalDataPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-102">Initializes a new instance of the ExternalDataPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDelay">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DataDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DataDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.DataDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDelay As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DataDelay : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.DataDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b9bc-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-103">Optional.</span></span> <span data-ttu-id="1b9bc-104">データの遅延です。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-104">Data delay.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumRetry">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.MaximumRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumRetry As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumRetry : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.MaximumRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b9bc-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-105">Optional.</span></span> <span data-ttu-id="1b9bc-106">最大再試行してください。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-106">Maximum retry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b9bc-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-107">Optional.</span></span> <span data-ttu-id="1b9bc-108">再試行の間隔。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-108">Retry interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.RetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Common.Models.ExternalDataPolicy.RetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b9bc-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-109">Optional.</span></span> <span data-ttu-id="1b9bc-110">アクティビティの実行に関するタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-110">Specifies the timeout for the activity to run.</span></span> <span data-ttu-id="1b9bc-111">指定された値がある場合、無制限のタイムアウトをつまり TimeSpan.FromMilliseconds(-1) の値を取ります。</span><span class="sxs-lookup"><span data-stu-id="1b9bc-111">If there is value specified, it takes the value of TimeSpan.FromMilliseconds(-1) which means indefinite timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>