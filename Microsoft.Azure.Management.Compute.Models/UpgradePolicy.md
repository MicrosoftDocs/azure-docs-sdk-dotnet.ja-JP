<Type Name="UpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Models.UpgradePolicy">
  <TypeSignature Language="C#" Value="public class UpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpgradePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.UpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class UpgradePolicy" />
  <TypeSignature Language="F#" Value="type UpgradePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            -自動、手動、またはローリングのアップグレード ポリシーをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UpgradePolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradePolicy (Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; mode = null, Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy rollingUpgradePolicy = null, Nullable&lt;bool&gt; automaticOSUpgrade = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; mode, class Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy rollingUpgradePolicy, valuetype System.Nullable`1&lt;bool&gt; automaticOSUpgrade) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.UpgradeMode},Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.UpgradePolicy : Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; * Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Compute.Models.UpgradePolicy" Usage="new Microsoft.Azure.Management.Compute.Models.UpgradePolicy (mode, rollingUpgradePolicy, automaticOSUpgrade)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mode" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt;" />
        <Parameter Name="rollingUpgradePolicy" Type="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" />
        <Parameter Name="automaticOSUpgrade" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="mode">スケール セット内の仮想マシンへのアップグレードのモードを指定します。&lt;ブラジル/&gt;&lt;ブラジル/&gt;値を指定できます:&lt;ブラジル/&gt;&lt;ブラジル/&gt; **手動**-更新プログラムの適用を制御します。仮想マシン スケール セットにします。 ManualUpgrade アクションを使用してこれを行います。&lt;ブラジル/&gt;&lt;ブラジル/&gt; **自動**-スケール セット内のすべての仮想マシンが同時に自動的に更新します。 使用可能な値が含まれます '自動'、'手動'、'ロールバック'。</param>
        <param name="rollingUpgradePolicy">ローリング アップグレードの実行中に使用される構成パラメーター。</param>
        <param name="automaticOSUpgrade">かどうか OS のアップグレードを自動的に適用するときに、新しいバージョンのイメージのローリングの方法でセット インスタンスのスケールが表示されます。</param>
        <summary>
            UpgradePolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutomaticOSUpgrade">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutomaticOSUpgrade { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutomaticOSUpgrade" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.AutomaticOSUpgrade" />
      <MemberSignature Language="VB.NET" Value="Public Property AutomaticOSUpgrade As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutomaticOSUpgrade : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.UpgradePolicy.AutomaticOSUpgrade" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="automaticOSUpgrade")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OS のアップグレードは、イメージの新しいバージョンが利用可能になったらローリング方式でセット インスタンスのスケールに自動的に適用する必要があるかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As Nullable(Of UpgradeMode)" />
      <MemberSignature Language="F#" Value="member this.Mode : Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.UpgradePolicy.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.UpgradeMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、スケール セット内の仮想マシンへのアップグレードのモードを指定します。&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;指定できる値は:&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;**手動**-仮想マシン スケール セットに更新プログラムの適用を制御します。 ManualUpgrade アクションを使用してこれを行います。&amp;lt; ブラジル/&amp;gt;&amp;lt; ブラジル/&amp;gt;**自動**-スケール セット内のすべての仮想マシンが同時に自動的に更新します。
            使用可能な値が含まれます '自動'、'手動'、'ロールバック'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollingUpgradePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy RollingUpgradePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy RollingUpgradePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.RollingUpgradePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RollingUpgradePolicy As RollingUpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradePolicy : Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy with get, set" Usage="Microsoft.Azure.Management.Compute.Models.UpgradePolicy.RollingUpgradePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rollingUpgradePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローリング アップグレードの実行中に使用する構成パラメーターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.UpgradePolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="upgradePolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>