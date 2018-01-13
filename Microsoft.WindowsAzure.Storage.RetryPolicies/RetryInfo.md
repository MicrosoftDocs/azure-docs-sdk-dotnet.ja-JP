<Type Name="RetryInfo" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo">
  <TypeSignature Language="C#" Value="public sealed class RetryInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryInfo" />
  <TypeSignature Language="F#" Value="type RetryInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9534-101">次の再試行まで、ターゲットの場所と配置モード、次の再試行間隔を含む、Microsoft Azure ストレージ サービスに対して行われる要求の次の再試行のパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="f9534-101">Specifies parameters for the next retry of a request to be made against the Microsoft Azure storage services, including the target location and location mode for the next retry and the interval until the next retry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9534-102"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f9534-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryInfo (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.#ctor(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo retryContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
      </Parameters>
      <Docs>
        <param name="retryContext"><span data-ttu-id="f9534-103"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />再試行ポリシーに渡されたオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9534-103">The <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> object that was passed in to the retry policy.</span></span></param>
        <summary>
            <span data-ttu-id="f9534-104"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f9534-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : TimeSpan with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9534-105">次の再試行までの間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="f9534-105">Gets the interval until the next retry.</span></span>
            </summary>
        <value><span data-ttu-id="f9534-106">A<see cref="T:System.TimeSpan" />次の再試行までの間隔を指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9534-106">A <see cref="T:System.TimeSpan" /> object specifying the interval until the next retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLocation As StorageLocation" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Microsoft.WindowsAzure.Storage.StorageLocation with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.TargetLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9534-107">取得または次の再試行のターゲットの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9534-107">Gets or sets the target location for the next retry.</span></span>
            </summary>
        <value><span data-ttu-id="f9534-108"><see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="f9534-108">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="retryInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9534-109">現在の <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> インスタンスを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="f9534-109">Returns a string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="f9534-110">現在を表す文字列<see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="f9534-110">A string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedLocationMode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode UpdatedLocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode UpdatedLocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.UpdatedLocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedLocationMode As LocationMode" />
      <MemberSignature Language="F#" Value="member this.UpdatedLocationMode : Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.UpdatedLocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9534-111">取得または以降の再試行の配置モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="f9534-111">Gets or sets the location mode for subsequent retries.</span></span>
            </summary>
        <value><span data-ttu-id="f9534-112"><see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="f9534-112">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>